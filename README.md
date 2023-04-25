# Elm アプリケーションテンプレート

## VSCode 拡張追加

https://marketplace.visualstudio.com/items?itemName=Elmtooling.elm-ls-vscode

## Node.js バージョン設定(任意)

```
nodenv local 16.14.0
```

## Node.js 利用準備

```
yarn init -y
```

## Elm 追加

```
yarn add elm
```

## Elm フォーマッター追加

```
yarn add --dev elm-format
```

## VSCode の自動フォーマット設定(任意)

.vscode/settings.json に追加

```
{
  "editor.formatOnSave": true,
}
```

## Elm 初期化

```
yarn elm init
```

## Main ファイル作成

```
touch ./src/Main.elm
```

- Main.elm に公式のガイド(https://guide.elm-lang.jp/)から適当なコードを貼り付けておく

## 実行

```
yarn elm reactor
```

## コンパイル

```
yarn elm make src/Main.elm
```

index.html が生成される
