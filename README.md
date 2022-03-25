Setup for my mac

# setup steps

## install homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## install homebrew formulae

```
brew bundle
```

## create symlink for zshrc

```
ln -s $PWD/.zshrc ~/.zshrc
```

## ssh key setup

see [this](https://docs.github.com/ja/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
