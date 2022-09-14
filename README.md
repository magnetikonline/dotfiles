# dotfiles - Linux

- [Highlights](#highlights)
- [Editor font](#editor-font)
	- [Current](#current)
	- [Previous](#previous)
- [Visual Studio Code extensions](#visual-studio-code-extensions)
- [Sublime Text 3 packages](#sublime-text-3-packages)

## Highlights

- `.gitconfig`
	- [aliases](.gitconfig#L38-L59).
	- Work/personal [profile switching](.gitconfig#L61-L62) based on repository path.
	- [userdiff](.gitattributes-global) config.
- Some useful Bash aliases in [`~/.bashrcmagnetik`](.bashrcmagnetik#L48-L80).
- [Visual Studio Code](https://code.visualstudio.com/) user settings.
- [Sublime Text 3](https://www.sublimetext.com/3) user settings.

## Editor font

### Current

- [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono).
- Configured with:
	- [Visual Studio Code](.config/Code/User/settings.json#L7-L9).
	- [Sublime Text 3](.config/sublime-text-3/Packages/User/Preferences.sublime-settings#L52-L56).

### Previous

- [FiraCode](https://github.com/tonsky/FiraCode).
- [Input](http://input.fontbureau.com/).
	- [Preview configured font stack](http://input.fontbureau.com/preview/?size=14&language=python&theme=solarized-dark&family=InputMono&width=200&weight=400&line-height=1.1&a=0&g=0&i=0&l=0&zero=0&asterisk=0&braces=0&preset=default&customize=please).

## Visual Studio Code extensions

```sh
$ code --list-extensions --show-versions
darkriszty.markdown-table-prettify@3.6.0
dbaeumer.vscode-eslint@2.2.6
EditorConfig.EditorConfig@0.16.4
golang.go@0.35.2
hashicorp.terraform@2.24.0
ms-azuretools.vscode-docker@1.22.0
ms-python.python@2022.14.0
ms-python.vscode-pylance@2022.9.10
PKief.material-icon-theme@4.20.0
redhat.vscode-yaml@1.10.1
streetsidesoftware.code-spell-checker@2.7.3
william-voyek.vscode-nginx@0.7.2
```

## Sublime Text 3 packages

- [AlignTab](https://github.com/randy3k/AlignTab)
- [EditorConfig](https://github.com/sindresorhus/editorconfig-sublime)
- [GitGutter](https://github.com/jisaacks/GitGutter)
- [Gofmt](https://github.com/noonat/sublime-gofmt)
- [LineEndings](https://github.com/titoBouzout/LineEndings)
- [Nginx](https://github.com/brandonwamboldt/sublime-nginx)
- [SCSS](https://github.com/P233/Syntax-highlighting-for-Sass)
- [SublimeJEDI](https://github.com/srusskih/SublimeJEDI)
- [TodoReview](https://github.com/jonathandelgado/SublimeTodoReview)
