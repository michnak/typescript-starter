# TypeScript Starter | 2024

tldr: A repo where all the tooling is already configured (with sensible defaults) and you can simply copy it and start building.

## The motivation

I often have an idea and want to start building right away, but then setting up the project saps part of excitement away.

Additionally, if you're not used to setting up new projects, it can be overwhelming and it leads to not properly configured projects:

- You don't know which version of the Node you should use
- Too lenient TypeScript config (or as I like to call it JavaScript with extra steps)
- Where ESlint and Prettier don't work together
- Where poorly formatted code slips in because one developer uses Vim and doesn't use Prettier

## Features

- TypeScript 5+
- Reloading with Nodemon and ts-node
- Export and import (ES modules) enabled
- ESlint
- Prettier
- Husky for pre-commit hook and lint-staged to format only staged files
- Rimraf for production build and start
- Jest for testing(can be excluded by switching to branch [without-jest](https://github.com/michnak/typescript-starter/tree/without-jest))

## How to run

1. Copy the repo

2. `npm install`

3. `npm run dev` to start the app in local developement

---

Inspired by [Khalil Stemmler](https://khalilstemmler.com/blogs/typescript/node-starter-project/)
