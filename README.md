# Vite React Typescript ESLint Sass Template

This is a template for creating a React project with Vite, Typescript, ESLint, Sass

## Quick Start using degit

#### _NOTE: need to install degit first with `npm i -g degit`_

```bash
degit emanuelefavero/vite-react-app my-app
cd my-app
npm install
npm run dev
```

## Usage

- clone this repo
- run `npm install`
- run `npm run dev` to start the vite dev server
- run `npm run host` to start the vite dev server with host
- run `npm run build` to build the project
- run `npm run preview` to preview the build

## Features

- Vite
- React
- Typescript
- ESLint
- Prettier (I've added a .prettierrc file with my personal settings but I've not added prettier as a dependency since I just use the prettier extension in VSCode)
- Sass

## Recreate this template from scratch

- run `npm create vite@latest my-vite-app --template react-ts`
- cd into the project
- run `npm install`
- run `eslint --init` and choose your preferred options
- add these rules in .eslintrc.json (suppress errors for missing 'import React' in files)

```json
    "react/react-in-jsx-scope": "off",
    "react/jsx-filename-extension": [
      1,
      { "extensions": [".js", ".jsx", ".ts", ".tsx"] }
    ]
```

- run `npm install -D sass`
- change `App.css` to `App.scss`
- start coding!
