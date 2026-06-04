<div align="center">

# 📢 TypeScript task 3 — ambient declarations

**Importing a plain-JavaScript library — by writing its types yourself.**

[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Webpack](https://img.shields.io/badge/bundler-Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)](https://webpack.js.org)
[![Holberton](https://img.shields.io/badge/Holberton-Specialization-E44D26?style=flat-square)](https://www.holbertonschool.com)

</div>

---

## 📖 About this task

The `.d.ts` trick: `crud.js` is normal JavaScript (insertRow, deleteRow,
updateRow) with no types at all. This task writes `crud.d.ts` — an ambient
declaration file teaching the compiler what those functions accept and
return, backed by `RowID` and `RowElement` types from `interface.ts`.

With the declarations in place, `main.ts` can import and use the untyped
library *with full type checking* — the exact mechanism behind
`@types/*` packages and the whole DefinitelyTyped ecosystem.

## 📂 Files

| File | What it does |
|---|---|
| `js/main.ts` | Uses the crud functions — fully type-checked |
| `js/crud.d.ts` | The ambient declarations for the untyped library |
| `js/crud.js` | The plain-JavaScript library being wrapped |
| `js/interface.ts` | `RowID` and `RowElement` shared types |
| `package.json` | Task dependencies & build scripts |
| `tsconfig.json` | Compiler options |
| `webpack.config.js` | Bundler config |

## 🚀 Run it

```bash
cd task_3
npm install
npm run build     # webpack → bundle
npm run dev       # dev server, where configured
```

---

✍️ **Muhəmməd Abdullayev** · [![GitHub](https://img.shields.io/badge/@Abdullayews-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdullayews) · one of the projects in **[holbertonschool-web_react](../README.md)**
