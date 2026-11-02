🇺🇸 English · [🇧🇷 Português](README.pt-BR.md)

# clone-tabnews

A personal learning project: rebuilding [TabNews](https://www.tabnews.com.br) from scratch while following the [curso.dev](https://curso.dev) course.

## Context

[TabNews](https://github.com/filipedeschamps/tabnews.com.br) is an open-source community created by Filipe Deschamps and contributors, and [curso.dev](https://curso.dev), by Filipe Deschamps, teaches how to build it step by step. **All credit for the original idea, product and course goes to them.** This repository is just my own code written while taking the course; it is not affiliated with TabNews or curso.dev.

> **Status: early stage.** Only the initial Next.js setup and a placeholder page exist so far.

## What's inside

| Path | Contents |
| --- | --- |
| `package.json` | Next.js 15, React 18 and React DOM 18; a `dev` script (`next dev`) |
| `pages/index.js` | Home page file, still empty |
| `pages/products/index.js` | Placeholder page that renders "Produtos — Página de produtos em desenvolvimento." |
| `.gitignore` | Present but still empty |
| `LICENSE` | MIT |

## How to run

Requirements: Node.js 18.18 or newer and npm.

```bash
npm install
npm run dev
```

Then open <http://localhost:3000/products>.

Note: `pages/index.js` is currently empty, so the home page (`/`) will show a Next.js error until it exports a React component. `npm test` is the default npm placeholder and just exits with an error.

## What I learned / next steps

- Setting up a Next.js project manually (`npm init`, installing `next`, `react` and `react-dom`) and how the `pages/` folder maps files to routes.
- Next: add a home page component to `pages/index.js`.
- Next: fill `.gitignore` (at least `node_modules/` and `.next/`) before committing more.
- Next: keep following the course modules and commit in smaller, more frequent steps.

## Feedback and contributions welcome

This is a learning repo, so feedback is very welcome. Feel free to open an issue with suggestions, questions or corrections, or a small pull request (for example, setup fixes or clearer docs). If you are looking for the real project, contribute to [TabNews](https://github.com/filipedeschamps/tabnews.com.br) itself.

## License

[MIT](LICENSE) © Yago Macambira
