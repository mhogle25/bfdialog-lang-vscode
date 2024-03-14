# bfdialog-lang README

BFDialog is a dialog scripting syntax that has high customizability and simple mechanics. This package adds syntax highlighting (with more to come) to VS Code for BFDialog lang. Download this as a vsix package [here](https://drive.google.com/file/d/1lxIB3_qN_bhoh18ajXzemDkXCdaxDg6o/view?usp=sharing).

## Features

Works on files with extension `.bfdlg`

Highlights all closures, strings, numbers, and single-term calls. Highlights default CLI control commands: `[ if, else, reduce ]`, dialog control commands: `[ end ]`, default CLI operations: `[ echo ]`, and dialog operations: `[ pause, delay, speed, line, chapter, nametag ]`

## Requirements

The bfo/dialog-textbox C# library (UNDER CONSTRUCTION)

## Known Issues

Bracket syntax highlighting for non-immediate commands still happens inside of command closures, when everything inside of a command closure should should be immediate. Not sure how to fix this, any help appreciated.

## Release Notes

### 0.0.2

- Separated bfdialog syntax from bfcli syntax, treating bfcli as an embedded language

- Chapter headers are now considered strings

### 0.0.1

The very first release. Basic syntax highlighting.

---
