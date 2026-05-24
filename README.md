# sublime-purescript-syntax

PureScript syntax support up to 0.15.16 for Sublime Text 4.

## Installation

Install package from Package Control `PureScript Syntax` and switch syntax to `PureScript`.

## Testing

```bash
while fswatch -1 ./purescript.sublime-syntax; do rsync -a ./purescript.sublime-syntax ~/Library/Application\ Support/Sublime\ Text/Packages/PureScriptSyntax/; done
```

## Manual Installation

```bash
mkdir ~/Library/Application\ Support/Sublime\ Text/Packages/PureScriptSyntax
cp ./purescript.sublime-syntax  ~/Library/Application\ Support/Sublime\ Text/Packages/PureScriptSyntax/
cp ./comments.tmPreferences  ~/Library/Application\ Support/Sublime\ Text/Packages/PureScriptSyntax/
```
