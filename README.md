# VSCode Plugin: "Hello World!"

## Overview

VS Code extensions enable developers to customize and enhance the functionality of the editor. This guide provides an overview of VS Code extension development, including creating a simple "Hello World" extension.

### Basics of Creating a New Extension

- **Extension Types:** VS Code supports various extension types, including language support, themes, snippets, debuggers, etc.
- **Extension Manifest:** Defined by a `package.json` file containing metadata like name, version, description, and activation events.
- **Extension Language:** Develop using JavaScript or TypeScript.

### Structure of an Extension Project

- **Extension Workspace:** Typically consists of folders containing source code, configuration files, and assets.
- **Main Extension File:** Entry point where functionality is defined (e.g., `extension.ts` or `extension.js`).
- **Additional Files:** Include `package.json`, `README.md`, and configuration files.

### Key Concepts

- **Activation Events:** Determine when an extension activates and loads into VS Code (e.g., opening workspace, executing command).
- **Contribution Points:** Define where and how an extension contributes functionality (e.g., commands, menus, keybindings).
- **Extension API:** Provides an extensive API for interacting with the editor's UI, workspace information, and performing tasks.

## Step-by-Step Guide to Creating a "Hello World" Extension

Follow these steps to create a simple VS Code extension that prints "Hello World" when a command is executed:

### Step 1: Set Up Your Development Environment

1. Ensure Node.js is installed on your machine.
2. Install Yeoman globally by running:
   ```bash
   $ npm install --global yo generator-code
## Generating a New Extension Project

To generate a new extension project using Yeoman, run the following command in your terminal:

```bash
$ yo code
```

Choose "New Extension (TypeScript)" as the type of extension.

## Implementing the "Hello World" Functionality

1. Open the `src/extension.ts` file in your code editor.
2. Replace the content of `extension.ts` with the provided code snippet.

   ![code](https://github.com/Apurv428/VSCode-Plugin_Hello-World/assets/84929607/29a88f10-4ce4-4803-897f-dcc1256517bf)

## Testing Your Extension

1. Debug your extension by pressing `Ctrl+Shift+D` or selecting "Run & Debug" from the menu. Then press `F5` to run your extension.
2. This will open a new VS Code window titled "Extension Development."
3. In the Extension Development window, navigate to the command palette (`Ctrl+Shift+P`) and search for ‘>Say Hello’.
4. Select the command "Extension: Say Hello" from the command palette to trigger the execution of your extension, which displays the "Hello World!" message.

## Demo

[Here is the Demo](https://drive.google.com/file/d/1Tn65bYPPfZZ4xpmzBb4zXSrR7_9vvIL1/view?usp=sharing)
