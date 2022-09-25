# boilerplate-yarn-2-monorepo

Boilerplate monorepo with yarn 2

## Quick Start

```bash
git clone https://github.com/JHSeo-git/boilerplate-yarn-2-monorepo.git my-project

cd my-project

# yarn install
yarn

# yarn dlx install
yarn dlx @yarnpkg/sdks vscode
```

## Git Clear

```bash
rm rf .git

git init
```

## Configuration

you make and use workspaces in `apps/`, `packages/`.

- package.json

## Scripts

`yarn build`

- Run concurrently workspaces's build

`yarn dev`

- Run concurrently workspaces's dev

## samples

- nextjs app
- node package
