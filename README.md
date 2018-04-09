# Duck
This repo represents a minimal macOS application that displays a rubber duck image on your screen for when a physical rubber duck is not present. but a [rubber duck debugging session](https://rubberduckdebugging.com/) is needed.

Inspired by (and stolen from) the [Stack Exchange rubber duck April Fools' joke](https://meta.stackexchange.com/questions/308564/stack-exchange-has-been-taken-over-by-a-rubber-duck). Code is based off the minimal Electron application from the [Quick Start Guide](https://electronjs.org/docs/tutorial/quick-start) within the Electron documentation.

![Rubber Duck](duck.svg)

## Installation
The easiest option for installation is to download a pre-compiled binary from the [releases page](https://github.com/jessemillar/duck/releases). If you wish to work with the source, follow the instructions below:

### Run from Code
```
git clone https://github.com/jessemillar/duck.git
cd duck
npm install
npm start
```

### Build a Binary
```
npm install electron-packager -g
git clone https://github.com/jessemillar/duck.git
cd duck
electron-packager . --out dist --prune true --icon duck.icns --overwrite
```
