# tic-tac-toe

## This repo is managed by [Turborepo](https://turborepo.org/)

### Getting started

---

Clone the repo and install dependencies by running `yarn` command in the root of the project

### Development

To start developing run `yarn dev` in the root of the project, this will run `dev` script in all apps

### Adding new npm packages

Turborepo utilizes [workspaces](https://classic.yarnpkg.com/lang/en/docs/workspaces/), add new dependency by running `yarn workspace {app/package name} add {npm-package-name}` ex. `yarn workspace web add react-icons`

### Utilizing internal packages

To use internal package add it as a dev/dependency in app/package `package.json`

```json
// ex. web/package.json
{
  "dependencies": {
    "tsconfig": "*"
  }
}
```
