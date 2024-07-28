# Monorepo template

## DevLog Specs

- pnpm v9.x.x
- Turborepo v2.x.x
- TypeScript v5
- husky v9
- eslint v8
- prettier v3
- commitlint v19

## Prepared to run server

### corepack

```bash
corepack enable
```

### Install Package modules

```bash
# add to global
pnpm install <package_name> -w
```

### Run Server

```bash
pnpm run <script_command> --filter <package_name>
```

### Add new app or package

```bash
pnpm turbo gen workspace --name <name> --type <app|package>
```
