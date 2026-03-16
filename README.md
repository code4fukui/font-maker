# font-maker

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A font creation tool for the IchigoJam dot font.

## Demo
[IchigoJam dot font](https://code4fukui.github.io/font-maker/IchigoJamdot-Regular.otf) (CC BY [IchigoJam](https://ichigojam.net/))

## Features
- Generates a TrueType font from a JSON-based glyph definition
- Includes a font for the IchigoJam dot matrix display

## Requirements
- [Deno](https://deno.land/)

## Usage
To generate the IchigoJam dot font:

```bash
deno run -A makeIchigoJamFont.js
```

This will create the `IchigoJamdot-Regular.otf` font file.

## Dependencies
- [opentype-es](https://github.com/code4fukui/opentype-es/)

## License
MIT License — see [LICENSE](LICENSE).