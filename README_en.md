# [pre-me-cli👌](https://github.com/baiziyu-fe/pre-me-cli)

>`#Quick react project generator`

![GitHub package.json version](https://img.shields.io/github/package-json/v/baiziyu-fe/pre-me-cli) ![npm](https://img.shields.io/npm/dw/pre-me-cli) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/baiziyu-fe/pre-me-cli) ![GitHub commit activity](https://img.shields.io/github/commit-activity/w/baiziyu-fe/pre-me-cli) ![GitHub last commit](https://img.shields.io/github/last-commit/baiziyu-fe/pre-me-cli) ![GitHub language count](https://img.shields.io/github/languages/count/baiziyu-fe/pre-me-cli) ![node-current](https://img.shields.io/node/v/react)


> A highly integrated `React` project generation scaffolding, so you don't have to worry about installing dependencies, and you don't have to repeatedly modify configuration files for custom configurations.
> Currently, `Webpack` and `Vite` are supported as project tools for startup, and `Javascript` and `Typescript` are supported.

#### 📎[中文｜Chinese](./README_zh.md)

---

<div align="center">
  <img src="./images/logo.png">
</div>

---

## Features🎉

### Real one step in place👏

1. Optimized and beautified the front-end project of `Webpack template`, and added packaging analysis and custom configuration.
2. `Webpack template` adds `Mock` test (based on `Koa`) and supports `Jest` for unit testing.
3. All templates support `alias` path configuration, server `Proxy` configuration, `postcss`, `less`, `eslint`, `prettier` and other functions.
4. All templates support customized configuration startup for different development environments.
5. Use `husky` to add `git commit` detection.
6. `React Router Dom` and support for different languages ​​have been added, providing quick start `Demo` and preset `file system management`.
7. You can use `npx` to always keep the template updated or use `npm` to install to make your favorite version stored locally.

### Highly self-modifying😯

1. Expose all configurable items to users, support more plug-in optimization and custom operations.
2. Provide users with a project template that is easier to use.

## Use 🔧

### method one:
   -Global installation: `npm install pre-me-cli -g`
   -Use the command to create a project template:

  ```
     pre-me-cli init [projectName]
     -webpack-ts
     -webpack-js
     -vite-ts
     -vite-js
  ```
### Method two (you can keep your template always up-to-date)
  -npx installation: `npx pre-me-cli init [projectName]`
  ```
     -webpack-ts
     -webpack-js
     -vite-ts
     -vite-js
  ```
### Startup project

-Enter the project and install dependencies: `cd projectName` && `yarn`
-Startup project: `yarn dev` or `npm run dev`


---

#### You are very welcome to provide some feasible suggestions and help, and look forward to your joining~
