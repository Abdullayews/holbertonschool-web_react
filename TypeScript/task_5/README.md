<div align="center">

# 🏷️ TypeScript task 5 — nominal typing

**Two identical shapes that refuse to mix: branding Major vs Minor credits.**

[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Webpack](https://img.shields.io/badge/bundler-Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)](https://webpack.js.org)
[![Holberton](https://img.shields.io/badge/Holberton-Specialization-E44D26?style=flat-square)](https://www.holbertonschool.com)

</div>

---

## 📖 About this task

TypeScript's typing is *structural* — same shape, same type. But real
domains need **nominal** distinctions: `MajorCredits` and `MinorCredits`
are both just `{ credits: number }`, yet passing one where the other
belongs should be an error.

The solution is **branding**: a `_brand: 'major'` / `_brand: 'minor'`
literal field makes the shapes incompatible, and `sumMajorCredits` /
`sumMinorCredits` can then add credits without ever mixing the two — the
lightweight version of what F#, C# and Rust give you for free.

## 📂 Files

| File | What it does |
|---|---|
| `js/main.ts` | MajorCredits, MinorCredits, and the two branded sums |
| `package.json` | Task dependencies & build scripts |
| `tsconfig.json` | Compiler options |
| `webpack.config.js` | Bundler config |

## 🚀 Run it

```bash
cd task_5
npm install
npm run build     # webpack → bundle
npm run dev       # dev server, where configured
```

---

✍️ **Muhəmməd Abdullayev** · [![GitHub](https://img.shields.io/badge/@Abdullayews-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdullayews) · one of the projects in **[holbertonschool-web_react](../README.md)**
