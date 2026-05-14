# font-maker

JavaScriptまたはJSONで定義されたグリフデータからOpenTypeフォントを生成するコマンドラインツールです。

## デモ
[IchigoJamドットフォント](https://code4fukui.github.io/font-maker/IchigoJamdot-Regular.otf) (CC BY [IchigoJam](https://ichigojam.net/))

## 機能
- OpenType（.otf）フォントをプログラムで生成します。
- ビットマップデータ（JSON経由）によるグリフ定義をサポートします。
- ベクターパス（JavaScript内）によるグリフ定義をサポートします。
- 8x8のIchigoJamドットフォントの完全なサンプルが含まれています。

## 要件
- [Deno](https://deno.land/)

## 使い方
このリポジトリには、フォントを生成するための2つのサンプルスクリプトが含まれています。

### 1. IchigoJamドットフォント（JSONのビットマップデータから）
このスクリプトは、`ichigojam-font.json`内のビットマップデータから`IchigoJamdot-Regular.otf`を生成します。

```bash
deno run -A makeIchigoJamFont.js
```

### 2. Pyramidフォント（ベクターデータから）
このスクリプトは、スクリプト内で直接定義されたベクター座標から`Pyramid-Regular.otf`を生成します。

```bash
deno run -A makePyramidFont.js
```

## 依存関係
- [opentype-es](https://github.com/code4fukui/opentype-es/)

## ライセンス
MIT
