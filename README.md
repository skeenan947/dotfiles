# Installation
```
cd
ln -sf $PATH_TO_DOTFILES/.zshrc .zshrc
```
## Oh-My-zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
## Bullet-Train ZSH Theme:
```
cd ~/.oh-my-zsh/themes
wget http://raw.github.com/caiogondim/bullet-train-oh-my-zsh-theme/master/bullet-train.zsh-theme
```

## Solarized Dark iTerm2 theme:
Download (Solarized Dark iTerm2 theme)[https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Solarized%20Dark%20-%20Patched.itermcolors]
```
wget -O Solarized-Dark.itermcolors https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Solarized%20Dark%20-%20Patched.itermcolors
open Solarized-Dark.itermcolors
```
iTerm2 Preferences -> Colors -> Color Presets -> Solarized Dark

## Fonts
Download powerline fonts:
```
wget -O MesloPowerline.ttf  https://github.com/powerline/fonts/raw/master/Meslo%20Slashed/Meslo%20LG%20M%20Regular%20for%20Powerline.ttf
open MesloPowerline.ttf
```
Set this font in iTerm2 (14px is my personal preference) (iTerm → Preferences → Profiles → Text → Change Font).

## Syntax highlighting

```
brew install zsh-syntax-highlighting
```

If you do not have or do not like homebrew, follow [the installation instructions](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md) instead.

After installation through homebrew, add

```
source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```

to the end of your `.zshrc` file
