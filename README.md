# ComputerCraft-TS
> [!NOTE]
> This document is AI-generated.

A template for developing ComputerCraft programs using TypeScript.

## Getting Started

### Prerequisites

*   [Node.js](https://nodejs.org/)
*   [pnpm](https://pnpm.io/)

### Installation

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2.  Install dependencies:
    ```bash
    pnpm install
    ```

### Building

To build the project, run the following command:

```bash
pnpm build
```

This will compile the TypeScript code in `src/` to Lua and output it to the `dist/` directory.

## Usage

After building the project, you can copy the compiled Lua code from the `dist/` directory to your ComputerCraft computer.

## Project Structure

*   `src/main.ts`: The main entry point of your program.
*   `tsconfig.json`: TypeScript compiler options.
*   `package.json`: Project metadata and dependencies.
*   `scripts/postbuild.js`: A script that runs after the build process.

## Dependencies

*   [TypeScriptToLua](https://github.com/TypeScriptToLua/TypeScriptToLua): A TypeScript to Lua compiler.
*   [typescript-tstl-plugin](https://github.com/TypeScriptToLua/TypeScriptToLua/tree/master/packages/typescript-tstl-plugin): A plugin for TypeScriptToLua.
