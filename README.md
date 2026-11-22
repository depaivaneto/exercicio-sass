# Exercício SASS - EBAC

Projeto original convertido de CSS para SCSS, mantendo o layout e os breakpoints.

## Organização

- `index.html`: página do projeto.
- `styles.css`: CSS compilado que o navegador utiliza.
- `scss/main.scss`: arquivo principal que importa os módulos com `@use`.
- `scss/_variables.scss`: cores, fonte, largura e espaçamentos reutilizáveis.
- `scss/_base.scss`: reset, corpo, container e seções.
- `scss/_header.scss`: cabeçalho e menu.
- `scss/_products.scss`: grade de produtos e botão.
- `scss/_responsive.scss`: ajustes para tablet e celular.

## Como compilar o SASS

No terminal, dentro da pasta do projeto:

```bash
npm install
npm run sass
```

Para recompilar automaticamente enquanto edita:

```bash
npm run sass:watch
```

O HTML já está apontando para `styles.css`, que é gerado a partir de `scss/main.scss`.
