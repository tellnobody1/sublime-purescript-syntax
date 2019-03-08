# sublime-purescript-syntax

PureScript syntax support for Sublime Text 3

## Installation

Install package from Package Control `PureScript Syntax` and switch syntax to `PureScript`.

## Testing

```bash
while fswatch -1 ./purescript.sublime-syntax; do rsync -a ./purescript.sublime-syntax ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/PureScriptSyntax/; done
```

## Manual Installation

```bash
mkdir ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/PureScriptSyntax
cp ./purescript.sublime-syntax  ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/PureScriptSyntax/
cp ./comments.tmPreferences  ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/PureScriptSyntax/
```
