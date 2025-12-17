# create-expo-themes 🎨

A powerful CLI tool to kickstart your Expo projects with pre-configured themes and styling engines. Skip the boilerplate and start building immediately with a clean, organized architecture.

## Features

*  Zero Config: Get a project running in seconds.
*  Two Styling Options: Choose between the standard StyleSheet API or NativeWind (Tailwind CSS).
*  Dark Mode Ready: Built-in support for light and dark themes.
*  Automatic Optimization: Automatically updates Expo SDK dependencies and runs `expo install --fix`.
*  Clean Architecture: Pre-organized folders for components, constants, and hooks.

## Quick Start

You don't need to install anything globally. Just run:

```bash
npx create-expo-themes
```

Or specify a project name directly:

```bash
npx create-expo-themes my-new-app
```

## Choose Your Flavor

The CLI allows you to choose between two professionally maintained starter kits:

### 1. Standard Theme Starter

Best for developers who prefer the default native React Native approach.

* Styling: React Native `StyleSheet` API.
* repository: https://github.com/KodeckJames/Expo-Themes-Starter-Kit

### 2. NativeWind Theme Starter

Best for developers who want the speed of utility classes.

* Styling: Tailwind CSS via NativeWind.
* Theming: Class-based dark mode switching.
* Config: Pre-configured `tailwind.config.js` and PostCSS setup.
* repository: https://github.com/KodeckJames/Expo-Nativewind-Themes-Starter-Kit

## What's Inside?

When you generate a project, the CLI performs the following steps:

1. Clones the selected template.
2. Updates core Expo dependencies to the latest stable SDK version.
3. Optimizes peer dependencies via `expo install --fix`.
4. Installs all npm packages.
5. Initializes a Git repository and creates an initial commit.

## Contributing

This is an open-source project! If you have a theme or a styling engine you'd like to add as a template, feel free to open an issue or a PR on the GitHub repository.

---

Created with ❤️ by Kodeck James