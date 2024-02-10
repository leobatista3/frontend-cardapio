#FRONT END CARDAPIO

Simples aplicação fullstack do zero usando Java Spring, React e PostgreSQL. Nesse repositório desenvolvemos o Frontend da nossa aplicação utilizando React, Typescript e React Query.

Também exploramos o uso de Typescript para garantir uma melhor manutenibilidade do código. Além disso, conectamos com o backend já construído no repositório anterior, utilizando a biblioteca Axios para fazer as requisições HTTP e React Query para buscar, armazenar em cache, sincronizar e atualizar o estado do servidor na nossa aplicação.

# FUNCIONALIDADE

Existe um botão no projeto que serve para adicionar mais itens no cardápio, onde é informado o item, o preço e a URL para uma imagem.

#FERRAMENTAS

* Axios
* VScode
* React
* Node
* NPM
* Typescript
* React Query
* Vite

# IMAGENS

![image](https://github.com/leobatista3/frontend-cardapio/assets/72052192/5b887306-9102-463e-8ab0-de09bf638237)

![image](https://github.com/leobatista3/frontend-cardapio/assets/72052192/f56008f6-5fbc-4de9-b7fc-43405adcaf2f)



# React + TypeScript + Vite

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
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
