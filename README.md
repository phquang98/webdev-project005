# FE Test

Setup FE envi
Main Tech: Vite + React + TS + Antd

## Instructions

- npm run dev

## How to create

- `npm create vite@latest . -- --template react-ts`
- Deps: `npm i react-router-dom react-icons axios cors uuid`
- Dev deps ESLint + TS + React: `npm i -D typescript eslint prettier husky@4.3.8 lint-staged @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-eslint-comments eslint-import-resolver-typescript eslint-plugin-prettier eslint-config-prettier`
- `npm i`

## Notes

assets need bundled, need to run through some loaders to minify, transforms -> `/assets`
media don't need processing -> `/public`

extends this rules for JSX Transform <https://github.com/jsx-eslint/eslint-plugin-react/blob/master/docs/rules/react-in-jsx-scope.md>
add project in here <https://typescript-eslint.io/architecture/parser/#project>
add eslintrcjson o tsconfig

## Resources

- <https://www.youtube.com/watch?v=cchqeWY0Nak>
