# hooksmith

Small typed hooks: debounce, localStorage, media query, toggle

Small but I use it weekly.

## Features

- Tiny: no dependencies besides React
- useMediaQuery SSR-safe
- useDebounce with leading/trailing options
- useLocalStorage with JSON serialization

## Install

```bash
npm install
npm test
```

## How to use

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Project structure

```text
├── .github/
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── config.js
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
└── package.json
```
