# 🚀 Vanilla JS + Vite

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Vite](https://img.shields.io/badge/vite-4.x-646CFF.svg?logo=vite)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E.svg?logo=javascript)
![ESLint](https://img.shields.io/badge/ESLint-8.x-4B32C3.svg?logo=eslint)

Un moderno boilerplate per applicazioni web JavaScript con bundler Vite. Progettato per offrire un'esperienza di sviluppo veloce e ottimizzata con un approccio minimalista e leggero, supportando funzionalità 100% offline.

## 📋 Table of Contents
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Setup & Development](#-setup--development)
- [Package Managers](#-package-managers)
- [Resources](#-resources)

## ✨ Features

- 🔄 Hot Module Replacement (HMR) per sviluppo rapido
- ⚡ Vite per un bundling ultra-veloce
- 💾 Supporto completo per funzionalità offline (localStorage)
- 📤 Possibilità di implementare export/backup dei dati
- 📊 Struttura per implementare dashboard e statistiche
- 🗓️ Supporto per timeline e viste calendario
- 🔍 Configurazione ESLint integrata
- 🌐 Web application ottimizzata per la distribuzione

## 🗂️ Project Structure

```
bl-vitejs-javascript/
├── public/             # Risorse statiche
├── src/
│   ├── assets/         # Immagini, font e risorse varie
│   ├── modules/        # Moduli JavaScript
│   ├── utils/          # Funzioni di utilità
│   ├── index.html      # Template HTML
│   ├── style.css       # Stili globali
│   └── main.js         # Entry point dell'applicazione
├── .eslintrc.cjs       # Configurazione ESLint
├── index.html          # Template HTML root
├── package.json        # Dipendenze e script
└── vite.config.js      # Configurazione Vite
```

## 🚀 Setup & Development

### 📥 Installazione

```bash
# Utilizzando NPM
$ npm install

# Utilizzando Yarn
$ yarn

# Utilizzando PNPM
$ pnpm install
```

### 🔧 Sviluppo

```bash
# Utilizzando NPM
$ npm run dev

# Utilizzando Yarn
$ yarn dev

# Utilizzando PNPM
$ pnpm dev
```

### 📦 Build

```bash
# Utilizzando NPM
$ npm run build

# Utilizzando Yarn
$ yarn build

# Utilizzando PNPM
$ pnpm build
```

### 🔍 Preview

```bash
# Utilizzando NPM
$ npm run preview

# Utilizzando Yarn
$ yarn preview

# Utilizzando PNPM
$ pnpm preview
```

## 📦 Package Managers

Questo progetto supporta diversi package manager. Ecco le caratteristiche di ciascuno:

### NPM

NPM è il package manager predefinito per Node.js.

**Installazione NPM:**
```bash
# Incluso con l'installazione di Node.js
```

**Caratteristiche principali:**
- 📚 Vasto ecosistema di pacchetti
- 🔒 Struttura gerarchica di node_modules
- 📋 Package.json per la gestione delle dipendenze

### Yarn

Yarn è un'alternativa rapida, affidabile e sicura a NPM.

**Installazione Yarn:**
```bash
# Installazione tramite NPM
$ npm install -g yarn
```

**Caratteristiche principali:**
- ⚡ Velocità di installazione superiore
- 📦 Caching offline
- 🔒 Maggiore sicurezza con checksum
- 📋 yarn.lock per installazioni deterministiche

### PNPM

PNPM è un package manager efficiente in termini di spazio su disco.

**Installazione PNPM:**
```bash
# Installazione tramite NPM
$ npm install -g pnpm
```

**Caratteristiche principali:**
- 💾 Risparmio di spazio su disco tramite symlink
- 🚀 Velocità di installazione elevata
- 🔄 Storage con indirizzamento basato sul contenuto
- 📋 pnpm-lock.yaml per blocco delle dipendenze

### Confronto

| Funzionalità          | NPM     | Yarn    | PNPM    |
|-----------------------|---------|---------|---------|
| Utilizzo disco        | Alto    | Alto    | Basso   |
| Velocità installazione| Lenta   | Veloce  | Velocissima |
| Installazioni parallele| Limitato| Sì      | Sì      |
| Supporto workspaces   | Limitato| Buono   | Ottimo  |
| Modalità offline      | Limitato| Buono   | Buono   |
| Sicurezza             | Buona   | Migliore| Migliore|

## 📚 Resources

- [Vite Documentation](https://vitejs.dev/guide/)
- [JavaScript MDN Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [ESLint Documentation](https://eslint.org/docs/user-guide/)
- [NPM Documentation](https://docs.npmjs.com/)
- [Yarn Documentation](https://yarnpkg.com/getting-started)
- [PNPM Documentation](https://pnpm.io/motivation)
