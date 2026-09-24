# nodework

Learning TypeScript by building tiny CLIs

## Getting started

```bash
npm install
npm run build
```

## Usage

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Highlights

- npm link friendly
- Strict tsconfig, no any
- Ships as an ESM binary
- commander-based subcommands

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   └── development.md
├── examples/
│   └── quickstart.md
├── src/
│   └── index.ts
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```

## Why

Needed this for myself; figured others might too.
