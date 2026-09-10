# hooksmith

Small typed hooks: debounce, localStorage, media query, toggle

Started as a weekend hack, grew on me.

## Usage

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Install

```bash
npm install
npm test
```

## Features

- Tiny: no dependencies besides React
- useDebounce with leading/trailing options
- useMediaQuery SSR-safe
- useLocalStorage with JSON serialization

## Project structure

```text
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── bug_report.md
├── docs/
│   ├── configuration.md
│   └── development.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## License

MIT. Do whatever you want.
