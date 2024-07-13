# jeff-zsh-theme
Based off of [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme)

## Manual installation
- Download 'jeff.zsh-theme' from this repository, and move it into ~/.oh-my-zsh/custom/themes/
- Edit `~/.zshrc` so that `ZSH_THEME=jeff` and save it
- Run `source ~/.zshrc`

## Script installation
Run the following command:
```
rm -f ~/.oh-my-zsh/themes/jeff.zsh-theme && \
curl --output-dir ~/.oh-my-zsh/themes -O https://raw.githubusercontent.com/jbaranski/jeff-zsh-theme/main/jeff.zsh-theme && \
cat ~/.oh-my-zsh/themes/jeff.zsh-theme && \
source ~/.zshrc
```
