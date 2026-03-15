# font-maker

IchigoJamのドットフォントを作成するためのツールです。

## デモ
[IchigoJamドットフォント](https://code4fukui.github.io/font-maker/IchigoJamdot-Regular.otf) (IchigoJam CC BY ライセンス)

## 機能
- JSONベースのグリフ定義からTrueTypeフォントを生成
- IchigoJamのドットマトリックスディスプレイ用フォントを含む

## 必要環境
- [Deno](https://deno.land/)

## 使い方
IchigoJamドットフォントを生成するには以下のコマンドを実行します:

```bash
deno run -A makeIchigoJamFont.js
```

これにより、`IchigoJamdot-Regular.otf`フォントファイルが生成されます。

## ライセンス
MIT