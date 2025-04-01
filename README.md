# 🚀 Vanilla JS + Vite

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Vite](https://img.shields.io/badge/vite-4.x-646CFF.svg?logo=vite)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E.svg?logo=javascript)
![ESLint](https://img.shields.io/badge/ESLint-8.x-4B32C3.svg?logo=eslint)

A modern JavaScript web application boilerplate with Vite bundler. Designed to offer a fast and optimized development experience with a minimalist and lightweight approach, supporting 100% offline functionality.

**Topics:** `javascript` `vite` `web-app` `spa` `offline-first` `local-storage` `minimal` `lightweight` `esm`

## 📋 Table of Contents
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Project Setup](#-project-setup)
- [Package Managers](#-package-managers)
- [Resources](#-resources)

## ✨ Features

- 🔄 Hot Module Replacement (HMR) for rapid development
- ⚡ Ultra-fast build with Vite bundler
- 💾 Complete support for offline functionality (localStorage)
- 📤 Import/export and backup capabilities
- 📊 Support for dashboard and statistical visualizations
- 🗓️ Ability to implement timeline and calendar views
- 🔍 ESLint configuration for code quality
- 📦 ES Module support
- 🎨 Vanilla JavaScript with modern ES6+ features

## 🗂️ Project Structure

```
bl-vitejs-javascript/
├── public/             # Static assets
├── dist/               # Build output directory
├── src/
│   ├── assets/         # Project assets (images, fonts, etc.)
│   ├── modules/        # JavaScript modules
│   ├── utils/          # Utility functions
│   ├── index.html      # HTML template
│   ├── style.css       # Global styles
│   └── main.js         # Application entry point
├── .eslintrc.cjs       # ESLint configuration
├── index.html          # HTML template root
├── package.json        # Project dependencies and scripts
└── vite.config.js      # Vite configuration
```

## 🚀 Project Setup

### 📥 Install

```bash
$ pnpm install
```

### 🔧 Development

```bash
$ pnpm dev
```

### 📦 Build

```bash
$ pnpm build
```

### 🔍 Preview

```bash
$ pnpm preview
```

## 📦 Package Managers

This project supports multiple package managers. Here's how to use each one:

### NPM

NPM is the default package manager for Node.js.

**Install NPM:**
```bash
# Included with Node.js installation
```

**Setup project with NPM:**
```bash
# Install dependencies
$ npm install

# Run development server
$ npm run dev

# Build application
$ npm run build

# Preview production build
$ npm run preview
```

**Key features:**
- 📚 Vast package ecosystem
- 🔒 Hierarchical node_modules structure
- 📋 Package.json for dependency management

### Yarn

Yarn is a fast, reliable, and secure alternative to NPM.

**Install Yarn:**
```bash
# Install using NPM
$ npm install -g yarn
```

**Setup project with Yarn:**
```bash
# Install dependencies
$ yarn

# Run development server
$ yarn dev

# Build application
$ yarn build

# Preview production build
$ yarn preview
```

**Key features:**
- ⚡ Faster installation speeds
- 📦 Offline caching
- 🔒 Better security with checksums
- 📋 yarn.lock for deterministic installations

### PNPM

PNPM is a disk-space efficient package manager.

**Install PNPM:**
```bash
# Install using NPM
$ npm install -g pnpm
```

**Setup project with PNPM:**
```bash
# Install dependencies
$ pnpm install

# Run development server
$ pnpm dev

# Build application
$ pnpm build

# Preview production build
$ pnpm preview
```

**Key features:**
- 💾 Disk space savings through symlinks
- 🚀 Fast installation speeds
- 🔄 Content-addressable storage
- 📋 pnpm-lock.yaml for dependency lock

### Comparison

| Feature               | NPM     | Yarn    | PNPM    |
|-----------------------|---------|---------|---------|
| Disk usage            | High    | High    | Low     |
| Installation speed    | Slow    | Fast    | Fastest |
| Parallel installations| Limited | Yes     | Yes     |
| Workspace support     | Limited | Good    | Best    |
| Offline mode          | Limited | Good    | Good    |
| Security              | Good    | Better  | Better  |

## 📚 Resources

- [Vite Documentation](https://vitejs.dev/guide/)
- [JavaScript MDN Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [ESLint Documentation](https://eslint.org/docs/user-guide/getting-started)
- [NPM Documentation](https://docs.npmjs.com/)
- [Yarn Documentation](https://yarnpkg.com/getting-started)
- [PNPM Documentation](https://pnpm.io/motivation)
