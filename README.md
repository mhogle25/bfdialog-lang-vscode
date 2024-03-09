# bfdialog-lang README

BFDialog is a dialog scripting syntax that has high customizability and simple mechanics. This package adds syntax highlighting (with more to come) to VS Code for BFDialog lang. Download this as a vsix package [here](https://drive.google.com/file/d/1Mkk9pLZybn1LTJkLIZsyz7TumMKD2hbz/view?usp=sharing).

## Features

Works on files with extension `.bfdlg`

Highlights all closures, strings, numbers, and single-term calls. Highlights default CLI control commands: [ `if`, `else`, `reduce` ], dialog control commands: [ `end` ], default CLI operations: [ `echo` ], and dialog operations: [ `pause`, `delay`, `speed`, `line`, `chapter`, `nametag` ]

## Requirements

The bfo/dialog-textbox C# library (UNDER CONSTRUCTION)

## Known Issues

Bracket syntax highlighting still happens inside of chapter closures, when everything inside of a chapter should be text. Not sure how to fix this, any help appreciated.

## Release Notes

### 0.0.1

The very first release. Basic syntax highlighting.

---
