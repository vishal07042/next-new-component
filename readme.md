# next-new-component

next-new-component is a CLI for creating new React components for Next.js.

## Description

This project provides a command-line interface for generating new React components for Next.js projects. It allows users to create new components with ease, following a set of customizable configurations.

## Installation

To install next-new-component, run the following command:

```bash
npm install -g next-new-component
```

## Usage

Once installed, you can use `next-new-component` to quickly scaffold new components. For example, to create a new component named `MyNewComponent`, run:

```bash
next-new-component MyNewComponent
```

This command will create a new directory at `src/components/MyNewComponent` with the necessary files for a React component.

## Configuration

Configuration for `next-new-component` can be done through a global `.new-component-config.json` file in your home directory, a local `.new-component-config.json` file in your project's root directory, or via command-line arguments. For example, to specify the language as TypeScript when creating a component, you can use:

```bash
next-new-component MyNewComponent --lang ts
```

This will create the component files with a `.tsx` extension.

## Features

- Simple CLI interface for adding React components.
- Supports customization through configuration.
- Provides colorful terminal output for a better user experience.

## Development

To contribute to the development of `next-new-component`:

1. Fork and clone the Git repo.
2. Install dependencies with `yarn install` or `npm install`.
3. Set up a symlink by running `npm link` in the `next-new-component` directory.
4. Test your changes by creating components in a test React project.

## About

This project is a useful tool for quickly creating new React components in Next.js projects. While it is not actively maintained, it offers a straightforward way to generate boilerplate code for components.

For more information, you can visit the [GitHub repository](https://github.com/joshwcomeau/new-component).
