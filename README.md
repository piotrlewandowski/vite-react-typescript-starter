# A Vite + React + TypeScript Starter

Simple Vite + React + TypeScript Starter. It contains:
- [x] React 18 (v18.2.0)
- [x] Vite 5 (v5.2.10)
- [x] TypeScript 5 (v5.4.5)
- [x] ES6 linting with continuous linting on file change
- [x] Prettier

## Prerequisites

* [Node](https://nodejs.org/) (Make sure you have the node 18+ installed)

## Getting Started

1. Clone the repository `gh repo clone piotrlewandowski/vite-react-typescript-starter` (or if you're not using GitHub CLI: `git clone git@github.com:piotrlewandowski/vite-react-typescript-starter.git`)
2. If you're using NVM run `nvm use` inside project directory to use node version set in `.nvmrc` file
3. Run `npm install` or `npm i` to install all the dependencies
4. To begin development task, run `npm run dev`
5. Open [http://localhost:5173/](http://localhost:5173/)

## Available commands

- `npm run clean` - delete the `dist` folder
- `npm run dev` - start the dev server and watch for changes
- `npm run build` - create a production ready build in `dist` folder
- `npm run eslint:check` - execute ESLint check
- `npm run eslint:fix` - execute ESLint check and automatically fix problems
- `npm run test` - unit tests
- `npm run test:watch` - unit tests in watch mode
