# 📦 webpack Boilerplate for CMScom

Original: https://github.com/taniarascia/webpack-boilerplate

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# パッケージの使い方

## セットアップ

```
$ git clone git@github.com:cmscom/webpack-boilerplate-init.git
$ cd webpack-boilerplate-init
$ npm i
```

## 開発モード

開発コード

- src/index.js
- src/template.html

```
$ npm run start
```

http://localhost:5080/
が開く

## ビルド

```
$ npm run build
```

distフォルダに生成される

ビルド済みのファイルを確認

```
npm i -g http-server
```

```
cd dist && http-server
```

# パッケージの作り方

このパッケージを作っていく流れを記載


https://github.com/taniarascia/webpack-boilerplate を元に
2021年11月5日時点のものをコピーしたレポジトリを以下に作った
https://github.com/cmscom/webpack-boilerplate-init

webpack-boilerplate-init から必要なものを変更

## フォルダの作成

- config
- public
- src

## ファイルの作成

- package.json
- config/*
- scr/index.js
- src/template.html


## package.json

- CSS関係の設定を削除
- 属性情報の変更: "name", "version", "description"

# Author

- Original: [Tania Rascia](https://www.taniarascia.com)
- Customize: [Manabu TERADA](https://github.com/terapyon)

## License

This project is open source and available under the [MIT License](LICENSE).
