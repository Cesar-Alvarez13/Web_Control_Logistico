# React + TypeScript + Vite

Desarrollo del frontend de una aplicación web dirigida al jefe de área o administrador para optimizar la logística de entregas. La aplicación incluye módulos para la creación de rutas, asignación y seguimiento de su estado, así como la gestión eficiente de pedidos y facturas. Se desarrollará utilizando React, TypeScript, CSS, Vite y Tailwind, proporcionando una interfaz intuitiva y eficiente para la administración de las operaciones logísticas.

Tecnologias: React, TypeScript, CSS, Vite y Tailwind, Css, Figma, Image Creator in Bing

[![image.png](https://i.postimg.cc/MHng2Hmv/image.png)](https://postimg.cc/n9t3qH5J)

[![image.png](https://i.postimg.cc/YC6ZwJYf/image.png)](https://postimg.cc/QFM0QY6H)

[![image.png](https://i.postimg.cc/FKhqFDxt/image.png)](https://postimg.cc/xXFgtG7g)

[![image.png](https://i.postimg.cc/pT61ZxMx/image.png)](https://postimg.cc/7GSVHFLQ)

[![image.png](https://i.postimg.cc/c1Vd1GgV/image.png)](https://postimg.cc/9zt61SBp)

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json', './tsconfig.app.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
