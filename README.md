# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh



Add the following lines to package.json

  "homepage": "https://sanju9645.github.io/ReactLogin",

run,
   npm i gh-pages --save-dev


"scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist",
    "dev": "vite",
    "build": "vite build",
    "lint": "eslint . --ext js,jsx --report-unused-disable-directives --max-warnings 0",
    "preview": "vite preview"
  },

  on vite.config.js

  export default defineConfig({
  base: '/ReactLogin/',
  plugins: [react()],
})
