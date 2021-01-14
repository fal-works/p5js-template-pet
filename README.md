# p5.js Template PET

Template project for creating [p5.js](https://p5js.org/) sketches using the following tools:

- Code editor: [Visual Studio Code](https://code.visualstudio.com/)
- Other tools: [Prettier](https://prettier.io/), [ESLint](https://eslint.org/) (+ plugins) and [TypeScript](https://www.typescriptlang.org/).

## Usage

1. Install the two below if not yet installed:
    - [Visual Studio Code](https://code.visualstudio.com/)
    - [Node.js](https://nodejs.org/)

2. Create a project by copying this template, then open it with VS Code.

3. Run the command-line below, which will install several dependencies:

    ```shell
    npm install
    ```

4. Install the VS Code extensions:
    - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
    (from CLI: `code --install-extension dbaeumer.vscode-eslint`)
    - [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)  
    (from CLI: `code --install-extension esbenp.prettier-vscode`)

    Now ESLint and Prettier works automatically every time you save your code.

5. Feel free to edit `src/script.ts`.
6. Run the command-line below to build `dist/script.js`:

    ```shell
    npm run build
    ```

7. Open `dist/index.html` to see the result.

## Dependencies (npm)

### Important ones

- [Prettier](https://www.npmjs.com/package/prettier)
- [ESLint](https://www.npmjs.com/package/eslint)
- [TypeScript](https://www.npmjs.com/package/typescript)

### Type definitions

- [@types/p5](https://www.npmjs.com/package/@types/p5)

### ESLint plugins

- [eslint-config-prettier](https://www.npmjs.com/package/eslint-config-prettier)
- [@typescript-eslint/parser](https://www.npmjs.com/package/@typescript-eslint/parser)
- [@typescript-eslint/eslint-plugin](https://www.npmjs.com/package/@typescript-eslint/eslint-plugin)
- [@fal-works/eslint-config-p5js](https://www.npmjs.com/package/@fal-works/eslint-config-p5js)
