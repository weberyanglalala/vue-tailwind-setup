# vue-chat

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and
disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Initialization

- node v20.9.0
- https://vuejs.org/guide/quick-start.html

```sh
npm create vue@latest
```

```
Vue.js - The Progressive JavaScript Framework

✔ 請輸入專案名稱： … vue-chat
✔ 是否使用 TypeScript？ … 否
✔ 是否啟用 JSX 支援？ … 否
✔ 是否引入 Vue Router 進行單頁應用程式開發？ … 是
✔ 是否引入 Pinia 用於狀態管理？ … 是
✔ 是否引入 Vitest 用於單元測試 … 否
✔ 是否要引入一款端對端（End to End）測試工具？ › 不需要
✔ 是否引入 ESLint 用於程式碼品質檢測？ … 是
✔ 是否引入 Prettier 用於程式碼格式化？ … 是
✔ 是否引入 Vue DevTools 7 擴充元件以協助偵錯？（試驗性功能） … 否
```

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## ESLint Configuration

> ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs.

- https://eslint.org/docs/latest/use/getting-started

## ESLint Plugin for vue

- https://vuejs.org/style-guide/
- https://eslint.vuejs.org/

## Prettier Configuration
- https://prettier.io/docs/en/

## Tailwind CSS

- https://tailwindcss.com/docs/guides/vite#vue

### Install Dependencies

```
npm install -D tailwindcss postcss autoprefixer
```

### Create Tailwind, Postcss Configuration File

```sh
npx tailwindcss init -p
```

### Update `tailwind.config.js`

```js
/** @type {import('tailwindcss').Config} */
export default {
  content: ['./index.html', './src/**/*.{vue,js,ts,jsx,tsx}'],
  theme: {
    extend: {}
  },
  plugins: []
}
```

### Add tailwindcss to `main.css`

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Add tailwind prettier plugin

- https://github.com/tailwindlabs/prettier-plugin-tailwindcss

#### Install Dependencies

```
npm install -D prettier prettier-plugin-tailwindcss
```

#### Update `.prettierrc.json

```json
{
  "plugins": ["prettier-plugin-tailwindcss"]
}
```
