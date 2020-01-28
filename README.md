# Herramientas que uso en Mac.

Instalar [Homebrew](https://brew.sh/)
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Configurar git

```bash
$ rm '/usr/local/bin/git-cvsserver'
$ brew link --overwrite git
$ brew install git-lfs
$ git lfs install
```
Configuración de 
[SSH](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

Instalar comando Tree

```bash
$ brew install tree
```

Configurar git con VSCode.

```bash
$ git config --global core.editor 'code --wait'
```

Instalar iTerm2

```bash
$ brew cask install iterm2
```

Instalar ZSH
```bash
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

Instalar [Visual Studio Code](https://code.visualstudio.com/)

Usar Iterm y ZSH en VSCode en settings.json
```bash
    "terminal.external.osxExec": "iTerm.app",
    "terminal.integrated.shell.osx": "zsh"
```

Extensiones:
  * Auto Close Tag
  * Auto Rename Tag
  * Bracket Pair Colorizer 2
  * Dracula Official
  * ESLint
  * Prettier - Code formatter
  * Vetur
  * VSCode Great Icons
  * GitLens

Instalar [1Password](https://www.1password.com/)




## License
[MIT](https://choosealicense.com/licenses/mit/)