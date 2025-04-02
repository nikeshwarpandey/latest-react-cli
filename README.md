# Latest React CLI

A CLI tool to streamline the creation of React projects, components, and hooks with TypeScript and Jest.

## Features

- **Create React Projects**: Quickly scaffold a new React project with TypeScript and Jest.
- **Generate Components**: Easily create React components with TypeScript and testing files.
- **Generate Hooks**: Create custom React hooks with boilerplate code.

## Installation

Install the CLI globally using npm:
```bash
npm install -g latest-react-cli
```

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







