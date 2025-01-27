# Terminal

## Homebrew
[Install Homebrew](https://brew.sh/)

## Oh My Zsh
``` 
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Kitty
Terminal.
```bash 
brew install --cask kitty
```
Color theme.
```bash
kitten themes
```
Font
```bash
brew install font-fira-code-nerd-font
```
change font_family to `FiraCode Nerd Font Mono` in ```~/.config/kitty/kitty.conf```

## Powerlevel10k
Customize prompt.
```bash
brew install powerlevel10k
```

## Git
```
brew install git
```

## Pfetch
Show system info in terminal.
```
brew install pfetch
```
Add
```
export PF_ASCII="alpine"
pfetch
```
To the first line of ```~/.zshrc```, where "alpine" is the ASCII logo you want to print.


## Zoxide
An autojump command line tool.
```
brew install zoxide
```
Add 
```
eval "$(zoxide init zsh)"
```
to the last line of ```~/.zshrc```.

## zsh-syntax-highlighting
```
brew install zsh-syntax-highlighting
```
# VS code
