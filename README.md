# bfdialog-lang README

BFDialog is a dialog scripting syntax that has high customizability and simple mechanics. This package adds syntax highlighting (with more to come) to VS Code for the BFDialog syntax. Download this as a vsix package [here](https://drive.google.com/file/d/1AKoA3nzmrQNnbqsbbRp3M_vx2RXD-qB4/view?usp=sharing).

## Features

Works on files with extension `.bfdlg`

Highlights all closures, strings, numbers, and single-term calls. Highlights default CLI control commands: `[ if, else, reduce, eq ]`, dialog control commands: `[ end ]`, default CLI operations: `[ echo ]`, and dialog operations: `[ pause, delay, speed, line, chapter, nametag ]`. Also does special highlighting for constants like `$some` and `$none`.

## Requirements

The bfo/dialog-textbox C# library (UNDER CONSTRUCTION)

## Known Issues

Bracket syntax highlighting for non-immediate commands still happens inside of command closures, when everything inside of a command closure should should be immediate. Not sure how to fix this, any help appreciated.

## Release Notes

### 0.0.3

- Added special syntax highlighting for `$some` and `$none` constants

### 0.0.2

- Separated bfdialog syntax from bfcli syntax, treating bfcli as an embedded language

- Chapter headers are now considered strings

### 0.0.1

The very first release. Basic syntax highlighting.

---
