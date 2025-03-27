# React + TypeScript + Vite

Desarrollo del frontend de una aplicación web dirigida al jefe de área o administrador para optimizar la logística de entregas. La aplicación incluye módulos para la creación de rutas, asignación y seguimiento de su estado, así como la gestión eficiente de pedidos y facturas. Se desarrollará utilizando React, TypeScript, CSS, Vite y Tailwind, proporcionando una interfaz intuitiva y eficiente para la administración de las operaciones logísticas.

Tecnologias: React, TypeScript, CSS, Vite y Tailwind, Figma, Image Creator in Bing

![image](https://github.com/user-attachments/assets/fae799b7-49ab-47ff-b31f-3158b1e577e4)

![image](https://github.com/user-attachments/assets/cf061a22-d584-402e-85ed-108477306ee0)

![image](https://github.com/user-attachments/assets/26d40ef8-fee0-45c4-955f-7cdfc7976f88)

![image](https://github.com/user-attachments/assets/787f80f2-1c2f-4ed5-9117-994e2a68baae)

![image](https://github.com/user-attachments/assets/a96ab8b9-0f64-434c-831a-8e24dd7fe638)

![image](https://github.com/user-attachments/assets/8c838525-5ea7-4c10-900a-0a32a91849d6)



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
