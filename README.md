# Instalation - Uses (Mac)

## Install Homebrew

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Add To Path (Only Apple Silicon Macbooks)

```sh
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```
This step is not necessary in intel based macbooks.

## Install NeoVim

```sh
brew install neovim
```

## Install ripgrep

```sh
brew install ripgrep
```

## Setting up neovim config and plugins

First [fork](https://github.com/wgetDJ/nvim/fork) the following repo, so that you'll have your own config which you can modify in future, then install by cloning the
fork to your machine using one of the commands below, depending on your OS.

> **NOTE**
> Your fork's url will be something like this:
> `https://github.com/<your_github_username>/nvim.git`

<details><summary> HTTPS </summary>

> **NOTE**
> If you have forked the repo then replace `wgetDJ` with your github username.

```sh
git clone https://github.com/wgetDJ/nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```
</details>

<details><summary> SSH </summary>

> **NOTE**
> If you have forked the repo then replace `wgetDJ` with your github username.

```sh
git clone git@github.com:wgetDJ/nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```
</details>

### Post Installation
TODO:

- Post Installation Process
- Keymaps

