# termux-octo.th
读入 [`Chinese`](https://github.com/testingBOT9/termux-octo.th/blob/main/README(1).md)

A fork from [oh-my-termux](https://github.com/4679/oh-my-termux). Make your Termux colorful~

Add [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) terminal
environment and [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) to Termux, set color style (mostly from [Gogh](https://github.com/Mayccoll/Gogh) and Powerline font ([from powerline/fonts](https://github.com/powerline/fonts)). The oh-my-zsh theme defaults to agnoster, the color style defaults to Tango, and the font defaults to Ubuntu.

**This Repo uses the official source of Termux. In Mainland China, you may need to add the Termux application to the proxy list.**
## Use:
```shell
~ sh -c "$(curl -fsSL https://github.com/Cabbagec/termux-ohmyzsh/raw/master/install.sh)"
```

## Set Colors:
Run `chcolor` to change the color style, or
```shell
~ ./.termux/colors.sh
```

## Set font 
Run `chfont` to change the font, or:
```shell
~ ./.termux.fonts.sh
```

## Need software package: 
-curl
