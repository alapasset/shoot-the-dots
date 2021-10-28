# React Starter Application
---------------

## Getting Started

- The app assumed installed `Node.js` newer than `10.16.3 LTS`(recommend newer than v14.8.0).
  If you have not it yet, follow the official [Node.js Doc](https://nodejs.org/en/) to install it.
  
```bash
npm install
```

```bash
npm start
```

after that auto launch todo app on your default browser and code edit ready.

----------------------------------------------------------

## Stack

- [Create React App](https://github.com/facebook/create-react-app/releases/tag/v4.0.3) [v4.0.3](https://github.com/facebook/create-react-app/releases/tag/v4.0.3) (**Without eject**)
- [TypeScript](https://www.typescriptlang.org/) [v4.2.4](https://github.com/microsoft/TypeScript/releases/tag/v4.2.4)
- [ESLint](https://eslint.org/)
  - [eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier)
  - [@typescript-eslint/eslint-plugin](https://github.com/typescript-eslint/typescript-eslint#readme)

## 👩‍💻 Usage

### `npm start`

After that you'll seen the console which are server processes messages.  
Let's follow the message and put in URL `http://localhost:3000/` your browsers adressbar,  
and then you'll got todo app as same as Demo. let's modify under the `src/` code feel free!!

Official Docs: https://create-react-app.dev/docs/getting-started#npm-start-or-npm-start

### `npm build`

After that You'll get bundled and optimization stuff in `build` directory.  
Also you can run production build with `serve` local webserver modules.

```bash
npm global add serve
serve -s build
```

Official Docs: https://create-react-app.dev/docs/getting-started#npm-run-build-or-npm-build

### `npm lint`

[ESLint](https://eslint.org/) is at the top.
And setup [TypeScript ESLint](https://github.com/typescript-eslint/typescript-eslint), integrating [Prettier](https://prettier.io/) as a [eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier).

### `npm lint:fix`

run wtih eslint --fix option.

### `npm typecheck`

While developing and building, Babel stop transpile with TS error messages.
I can't find way static typecheck with babel,
so I'm using original TypeScript via npm and specified `tsc --noEmit` compile option that doesn't generate compiled code.
