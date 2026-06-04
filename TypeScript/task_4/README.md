<div align="center">

# 📦 TypeScript task 4 — namespaces & merging

**One Subjects namespace, extended five times without touching the original.**

[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Webpack](https://img.shields.io/badge/bundler-Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)](https://webpack.js.org)
[![Holberton](https://img.shields.io/badge/Holberton-Specialization-E44D26?style=flat-square)](https://www.holbertonschool.com)

</div>

---

## 📖 About this task

Declaration merging in practice: a `Subjects` namespace is spread across
files — `Teacher.ts` adds an interface, then `Subject.ts`, `Cpp.ts`,
`Java.ts` and `React.ts` each merge their classes and extensions into the
same namespace without ever editing the original files.

Each subject extends the shared `Teacher` with its own
`experienceTeachingX?` attribute, and exposes a `getRequirements()` +
`getAvailableTeacher()` pair — the pattern `@types/node` and other huge
declaration files are built from.

## 📂 Files

| File | What it does |
|---|---|
| `js/main.ts` | Builds teachers and prints every subject's requirements |
| `js/subjects/Teacher.ts` | The Teacher interface inside the namespace |
| `js/subjects/Subject.ts` | The abstract-ish base Subject class |
| `js/subjects/Cpp.ts` | C++ subject — experienceTeachingC |
| `js/subjects/Java.ts` | Java subject — experienceTeachingJava |
| `js/subjects/React.ts` | React subject — experienceTeachingReact |
| `package.json` | Task dependencies & build scripts |
| `tsconfig.json` | Compiler options |
| `webpack.config.js` | Bundler config |

## 🚀 Run it

```bash
cd task_4
npm install
npm run build     # webpack → bundle
npm run dev       # dev server, where configured
```

---

✍️ **Muhəmməd Abdullayev** · [![GitHub](https://img.shields.io/badge/@Abdullayews-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdullayews) · one of the projects in **[holbertonschool-web_react](../README.md)**
