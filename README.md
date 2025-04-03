# Latest React CLI
# https://www.npmjs.com/package/latest-react-cli
A CLI tool to streamline the creation of React projects, components, and hooks with TypeScript and Jest.

## Features

- **Create React Projects**: Quickly scaffold a new React project with TypeScript and Jest.
- **Generate Components**: Easily create React components with TypeScript and testing files.
- **Generate Hooks**: Create custom React hooks with boilerplate code.

Usage: cli [options] [command]

Options:
  -h, --help                            display help for command

Commands:
  create-project|crp <projectname>      Create react project with typescript and jest
  create-component|crc <componentname>  Creating a component
  create-hook|crh <hookname>            Create a hook
  help [command]                        display help for command

## Installation
npm or npx
Install the CLI globally using npm:
```bash
npm install -g latest-react-cli
```

 npm view latest-react-cli version
## Usage

### 1. Create a React Project
```bash
latest-react-cli create-project <projectname>
```
- Scaffolds a new React project with TypeScript and Jest.
- Example:
  ```bash
  latest-react-cli create-project my-app
  ```

### 2. Create a Component
```bash
latest-react-cli create-component <componentname>
```
- Generates a new React component with TypeScript and a corresponding test file.
- Example:
  ```bash
  latest-react-cli create-component MyComponent
  ```

### 3. Create a Hook
```bash
latest-react-cli create-hook <hookname>
```
- Creates a custom React hook with boilerplate code.
- Example:
  ```bash
  latest-react-cli create-hook useCustomHook
  ```

## Project Structure

- **bin/cli.js**: The main CLI script.
- **src/**: Contains the generated files for components and hooks.
  - **components/**: Directory for React components.
  - **hooks/**: Directory for custom hooks.

## License

This project is licensed under the ISC License.







