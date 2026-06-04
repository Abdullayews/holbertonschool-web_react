<div align="center">

# 🎭 TypeScript task 2 — advanced types

**Literal types, type predicates and polymorphic employees.**

[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Webpack](https://img.shields.io/badge/bundler-Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)](https://webpack.js.org)
[![Holberton](https://img.shields.io/badge/Holberton-Specialization-E44D26?style=flat-square)](https://www.holbertonschool.com)

</div>

---

## 📖 About this task

Structural typing meets logic: `TeacherInterface` and `DirectorInterface`
describe different work styles, implemented by `Teacher` and `Director`
classes. A `createEmployee(salary)` function returns either one based on a
literal-type branch — and an `isDirector()` **type predicate** lets
TypeScript narrow the union afterwards, so `executeWork()` can call the
right method on the right type, checked at compile time.

## 📂 Files

| File | What it does |
|---|---|
| `js/main.ts` | Interfaces, classes, createEmployee, isDirector, executeWork |
| `package.json` | Task dependencies & build scripts |
| `tsconfig.json` | Compiler options |
| `webpack.config.js` | Bundler config |

## 🚀 Run it

```bash
cd task_2
npm install
npm run build     # webpack → bundle
npm run dev       # dev server, where configured
```

---

✍️ **Muhəmməd Abdullayev** · [![GitHub](https://img.shields.io/badge/@Abdullayews-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdullayews) · one of the projects in **[holbertonschool-web_react](../README.md)**
