# package.json 導入および ESLint 導入の方法
---
## package.json ファイル作成

```
yarn init -y
```

`-y`の部分は全ての対話型項目を yes として進めるためのもの

## ESlint 導入

```
% yarn add eslint --dev
% yarn run eslint --init
```

`yarn add eslint --dev`で.eslintrc.js(設定ファイル)を作成  
`yarn run eslint --init`対話式でプロジェクトについて設定
