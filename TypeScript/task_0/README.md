<div align="center">

# 🧷 TypeScript task 0 — interfaces & the DOM

**A Student interface, two students, one real HTML table.**

[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Webpack](https://img.shields.io/badge/bundler-Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)](https://webpack.js.org)
[![Holberton](https://img.shields.io/badge/Holberton-Specialization-E44D26?style=flat-square)](https://www.holbertonschool.com)

</div>

---

## 📖 About this task

The warm-up: define a `Student` interface — `firstName`, `lastName`, `age`,
`location` — create two students, and render them into a **real DOM table**
using `document.createElement`. The TypeScript twist is that the DOM itself
gets typed: `HTMLTableElement`, `HTMLTableRowElement`,
`HTMLTableCellElement`, so the compiler checks your table-building too.

The task also sets up the webpack + babel build every following task
reuses, and adds ` professors`-style typing extensions in
`teacher.ts` / `director.ts`? — no, that's task 1. Task 0 stays pure:
interfaces + typed DOM.

## 📂 Files

| File | What it does |
|---|---|
| `js/main.ts` | Student interface + the typed table renderer |
| `package.json` | Task dependencies & build scripts |
| `tsconfig.json` | Strict compiler options for this task |
| `webpack.config.js` | The bundler entry (`js/main.ts` → `dist`) |

## 🚀 Run it

```bash
cd task_0
npm install
npm run build     # webpack → bundle
npm run dev       # dev server, where configured
```

---

✍️ **Muhəmməd Abdullayev** · [![GitHub](https://img.shields.io/badge/@Abdullayews-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdullayews) · one of the projects in **[holbertonschool-web_react](../README.md)**
