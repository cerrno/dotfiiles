# dotfiles

My personal environment configuration files

## Usage

Pull the repository, optionally install package dependencies `./install_deps.sh`, then create the symbolic links using GNU stow.
```bash
$ git clone git@github.com:cerrno/dotfiles.git ~/.dotfiles
$ cd ~/.dotfiles
$ stow fish git neovim
```

## VSCode

All non-essential `@builtin` extensions are disabled to improve startup time.
```bash
$ code --list-extensions
4ops.terraform
dracula-theme.theme-dracula
golang.go
James-Yu.latex-workshop
matklad.rust-analyzer
ms-azuretools.vscode-docker
ms-python.python
ms-python.vscode-pylance
ms-toolsai.jupyter
ms-toolsai.jupyter-keymap
ms-vscode.cpptools
ms-vscode.sublime-keybindings
serayuzgur.crates
svelte.svelte-vscode
tamasfe.even-better-toml
vadimcn.vscode-lldb
```
