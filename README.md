# jeff-zsh-theme
Based off of [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) ([src](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme))

<img width="1438" alt="Screenshot 2024-07-16 at 8 36 45 PM" src="https://github.com/user-attachments/assets/75e1e08c-bccf-4625-b8bf-29a7f04bed2c">


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

You can also `alias update_theme=<the command above>` to create a zsh alias for updating the theme.
