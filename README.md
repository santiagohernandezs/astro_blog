# Astro Starter Kit: Basics

```
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![basics](https://user-images.githubusercontent.com/4677417/186188965-73453154-fdec-4d6b-9c34-cb35c248ae5b.png)


## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:3000`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## ESLint Rules
This file contains a set of ESLint rules that are recommended for most projects. The rules are organized into three sections: Errors, Variables, and Formatting.

### Errors
These rules are designed to catch common errors in JavaScript code.

- `array-callback-return`: Ensures that the callback function returned by an array method always returns a value.
- `constructor-super`: Requires super() calls in constructors.
- `for-direction`: Ensures that the for loop iterates in the correct direction.
- `getter-return`: Ensures that getters always return a value.
- `no-async-promise-executor`: Prevents using the async keyword with the new keyword.
- `no-await-in-loop`: Prevents using the await keyword inside a for loop.
- `no-class-assign`: Prevents assigning classes to variables.
- `no-compare-neg-zero`: Prevents comparisons with -0.
- `no-cond-assign`: Prevents assigning conditional expressions to variables.
- `no-const-assign`: Prevents assigning constants to variables.
- `no-debugger`: Prevents the debugger statement from being used.
- `no-duplicate-imports`: Prevents duplicate imports.
- `no-empty`: Prevents empty statements.
- `no-empty-function`: Prevents empty functions.
- `no-eval`: Prevents the eval() function from being used.
- `no-extra-semi`: Prevents extra semicolons in the code.
- `no-fallthrough`: Prevents fallthrough in switch statements.
- `no-irregular-whitespace`: Prevents irregular whitespace in the code.
- `no-multiple-empty-lines`: Prevents more than two consecutive empty lines in the code.
- `no-new-wrappers`: Prevents the new keyword from being used with primitive types.
- `no-return-await`: Prevents the return keyword from being used with the await keyword.
- `no-trailing-spaces`: Prevents trailing spaces in the code.
- `no-undef`: Prevents variables from being used before they are defined.
- `no-unused-vars`: Prevents variables from being unused.

### Variables
These rules are designed to enforce good variable naming conventions and prevent common errors related to variables.

- `camelcase`: Requires variable names to be in camelCase.
- `no-global-assign`: Prevents assigning variables to global scope.
- `no-implicit-globals`: Prevents using implicit global variables.
- `no-unused-expressions`: Prevents unused expressions.
- `no-unused-labels`: Prevents unused labels.
- `prefer-const`: Prefers using const instead of var for declaring variables.

### Formatting
These rules are designed to enforce consistent code formatting.

- `indent`: Requires code to be indented by 2 spaces.
- `linebreak-style`: Requires line breaks to be UNIX style (\n).
- `quotes`: Requires single quotes to be used for strings.
- `semi`: Requires semicolons to be used at the end of statements.
- `space-before-function-paren`: Requires a space before the parenthesis in function declarations.
- `space-in-parens`: Requires no spaces inside parentheses.
- `space-infix-ops`: Requires a space around infix operators.
- `space-unary-ops`: Requires a space around unary operators.

### Other
These rules are not strictly errors, but they may be helpful to enforce in some projects.

- `no-console`: Disables the console object.
- `no-new`: Disables the new keyword.
-`no-throw-literal`: Disables throwing literal values.

`For more information on ESLint rules, please see the ESLint Rules Reference: https://eslint.org/docs/latest/rules/.
