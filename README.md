# bfdialog-lang

BFDialog is a dialog scripting syntax with high customizability and simple mechanics. This package adds syntax highlighting (with more to come) to VS Code for the BFDialog syntax. Download this as a vsix package [here](https://drive.google.com/file/d/1IGcJmEqZcARcY734ttimW72x5GpKcQAC/view?usp=sharing).

## Features

Works on files with extension `.bfdlg`

Highlights all closures, strings, numbers, and single-term calls. Highlights CLI operations: `[ if, else, first, eq, neq, lt, gt, lte, gte, llt, lgt, llte, lgte, exec, join, concat ]`, dialog control operations: `[ pause, delay, speed, line, chapter, nametag, end ]`, and dialog styling operations: `[ b, i, u, s, hint, font, lang, color, bgcolor, fgcolor, outline_size, outline_color, ctx, pop ]`. Also does special highlighting for constants like `$some` and `$none`.

## Requirements

The bfo/dialog-textbox C# library (alpha)

## Known Issues

- Bracket syntax highlighting for command closures happens within other command closures

- Parentheses are highlighted outside of command closures
---