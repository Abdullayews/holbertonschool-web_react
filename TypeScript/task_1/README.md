<div align="center">

# 🧑‍🏫 TypeScript task 1 — interfaces extended

**Teacher, Directors and a class built to constructor interfaces.**

[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Webpack](https://img.shields.io/badge/bundler-Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)](https://webpack.js.org)
[![Holberton](https://img.shields.io/badge/Holberton-Specialization-E44D26?style=flat-square)](https://www.holbertonschool.com)

</div>

---

## 📖 About this task

Interfaces get serious: a `Teacher` interface with `readonly` names, a
required `fullTimeEmployee`, an optional `yearsOfExperience` and an index
signature for extra attributes; a `Directors` interface *extending* it with
`numberOfReports`; and a `StudentClass` constrained by **two interfaces** —
one describing its constructor, one its instances — so the class can only
be built with a first & last name and always exposes `workOnHomework()` /
`displayName()`.

## 📂 Files

| File | What it does |
|---|---|
| `js/main.ts` | Teacher, Directors, StudentClass — the whole interface zoo |
| `package.json` | Task dependencies & build scripts |
| `tsconfig.json` | Compiler options |
| `webpack.config.js` | Bundler config |

## 🚀 Run it

```bash
cd task_1
npm install
npm run build     # webpack → bundle
npm run dev       # dev server, where configured
```

---

✍️ **Muhəmməd Abdullayev** · [![GitHub](https://img.shields.io/badge/@Abdullayews-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdullayews) · one of the projects in **[holbertonschool-web_react](../README.md)**
