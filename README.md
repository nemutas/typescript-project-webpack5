# TypeScript の VSCode 開発環境（webpack5 使用）

## How to use

[【TypeScript】VSCode で TypeScript の開発環境を構築する](https://qiita.com/nemutas/items/0a266ec58c76ae3ee43a)  
[【TypeScript】VSCode で TypeScript の開発環境を構築する ②（webpack ver.5）](https://qiita.com/nemutas/items/3a220aad4692f83bbbb5)

## Package Install

必要なパッケージファイル（node_modules）は含んでいません。  
最初に VSCode のターミナルで、以下を実行してパッケージをインストールしてください。

```
npm install --save-dev webpack webpack-cli webpack-dev-server typescript ts-loader clean-webpack-plugin
```

動作しているバージョンのインストール

```
npm install --save-dev webpack@5.36.2 webpack-cli@4.6.0 webpack-dev-server@3.11.2 typescript@4.2.4 ts-loader@9.1.1 clean-webpack-plugin@4.0.0-alpha.0
```

## Author

[nemutas](https://github.com/nemutas)
