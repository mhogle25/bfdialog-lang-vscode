# bfdialog-lang README

BFDialog is a dialog scripting syntax that has high customizability and simple mechanics. This package adds syntax highlighting (with more to come) to VS Code for the BFDialog syntax. Download this as a vsix package [here](https://drive.google.com/file/d/1-vH4HXRoi8N8KU3J786yc4em_NNoSVKu/view?usp=drive_link).

## Features

Works on files with extension `.bfdlg`

Highlights all closures, strings, numbers, and single-term calls. Highlights default CLI control commands: `[ if, else, reduce, eq, neq, lt, gt, lte, gte, llt, lgt, llte, lgte ]`, dialog control commands: `[ end ]`, default CLI operations: `[ echo ]`, dialog operations: `[ pause, delay, speed, line, chapter, nametag ]`, and dialog styling macros: `[ b, i, u, s, hint, font, lang, color, bgcolor, fgcolor, outline_size, outline_color ]`. Also does special highlighting for constants like `$some` and `$none`.

## Requirements

The bfo/dialog-textbox C# library (alpha)

## Known Issues

- Bracket syntax highlighting for non-immediate commands still happens inside of command closures, when everything inside of a command closure should should be immediate. Not sure how to fix this, any help appreciated.

- Syntax highlighting turns off after any closure created inside of another closure, until the next closure is declared or the outer closure ends, and only when that nested closure has content. Not sure how to fix this, any help appreciated.

## Release Notes

### 0.0.6

- Bug fixes

### 0.0.5

- Instant inserts

- Styling macros

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
