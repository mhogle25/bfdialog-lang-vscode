# bfdialog-lang

BFDialog is a dialog scripting syntax with high customizability and simple mechanics. This package adds syntax highlighting (with more to come) to VS Code for the BFDialog syntax. Download this as a vsix package [here](https://drive.google.com/file/d/1cy4oqid0XHxNmYPlhCTbg93u7Bm9RpS5/view?usp=sharing).

## Features

Works on files with extension `.bfdlg`

Highlights all closures, strings, numbers, and single-term calls. Highlights CLI operations: `[ if, else, first, eq, neq, lt, gt, lte, gte, llt, lgt, llte, lgte, exec, join, concat ]`, dialog control operations: `[ pause, delay, speed, line, chapter, nametag, end ]`, and dialog styling operations: `[ b, i, u, s, hint, font, lang, color, bgcolor, fgcolor, outline_size, outline_color, ctx, pop ]`. Also does special highlighting for constants like `$some` and `$none`.

## Requirements

The bfo/dialog-textbox C# library (alpha)

## Known Issues

- Bracket syntax highlighting for command closures happens within other command closures

- Parentheses are highlighted outside of command closures

## Release Notes

### 0.0.7

- Added new operations: `[ exec, join, concat ]`

- `reduce` renamed to `first`

### 0.0.6

- Bug fixes

### 0.0.5

- Instant inserts

- Styling operations

### 0.0.4

- Brackets are now parentheses

### 0.0.3

- Added special syntax highlighting for `$some` and `$none` constants

### 0.0.2

- Separated bfdialog syntax from bfcli syntax, treating bfcli as an embedded language

- Chapter headers are now considered strings

### 0.0.1

- The very first release. Basic syntax highlighting.

---
