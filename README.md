# font-maker

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A command-line tool for generating OpenType fonts from glyph data defined in JavaScript or JSON.

## Demo
[IchigoJam dot font](https://code4fukui.github.io/font-maker/IchigoJamdot-Regular.otf) (CC BY [IchigoJam](https://ichigojam.net/))

## Features
- Generates OpenType (.otf) fonts programmatically.
- Supports glyph definitions from bitmap data (via JSON).
- Supports glyph definitions from vector paths (in JavaScript).
- Includes a complete example for the 8x8 IchigoJam dot font.

## Requirements
- [Deno](https://deno.land/)

## Usage
This repository contains two example scripts for generating fonts.

### 1. IchigoJam Dot Font (from JSON bitmap data)
This script generates `IchigoJamdot-Regular.otf` from the bitmap data in `ichigojam-font.json`.

```bash
deno run -A makeIchigoJamFont.js
```

### 2. Pyramid Font (from vector data)
This script generates `Pyramid-Regular.otf` from vector coordinates defined directly in the script.

```bash
deno run -A makePyramidFont.js
```

## Dependencies
- [opentype-es](https://github.com/code4fukui/opentype-es/)

## License
MIT