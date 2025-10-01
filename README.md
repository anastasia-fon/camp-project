# camp-project

Monorepo with Angular, React and Vanilla TS for JS camp. Created with [Nx](https://nx.dev/).
## Installation

`npm install` to install all required dependencies.

## Usage

### Development

Run command to start development server

```bash
npm run [project]:serve
```

### Build

Run command to build the application.

```bash
npm run [project]:build
```

### Linting

To manually run `eslint` over your code, you can perform command in the terminal.

```bash
npm run [project]:lint
```

To manually run `stylelint` over your code, you can perform command in the terminal.

```bash
npm run [project]:stylelint
```

## Workspace structure

Workspace consists of applications and libraries. A lib contains the actual logic that can be shared across the workspace. An application is an unit that link, bundle and compile functionality implemented in libraries for being deployed.

### Applications

- [Vanilla](apps/vanilla/README.md)
- [React](apps/react/README.md)
- [Angular](apps/angular/README.md)

### Libraries

- [Core](libs/core/README.md)
- [Theme](libs/theme/README.md)
