# @jorenrui/create-project
> A personal CLI to boostrap new projects 👩‍💻

![NPM Version](https://img.shields.io/badge/npm-v0.1.0-orange)
![License Status](https://img.shields.io/badge/license-MIT-blue)

![create-project CLI](assets/cli.png)

## Features

- Quickly create project with a built-in javascript/typescript template.
- Built-in Git initialization.
- Built-in installation of dependencies.

## Installation

Install it using [yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/):

```bash
# Using NPM
npx @jorenrui/create-project
# or
npm install -g @jorenrui/create-project

# Using Yarn
yarn @jorenrui/create-project
```

## Usage

```bash
# Create a directory/folder
mkdir new-app

# Navigate to the created directory
cd new-app

# Run the cli
create-project
# or
create-project typescript --git
```

The cli will prompt you regarding what template to use and other configurations. You may skip it by adding `--yes`.

Currently there are two templates:
- JavaScript
- TypeScript

### Options

| command   | description                         |
|-----------|-------------------------------------|
| --yes     | Skip the questions.                 |
| --git     | Initialize the new project with git |
| --install | Install the dependencies            |

## License
[MIT](LICENSE)