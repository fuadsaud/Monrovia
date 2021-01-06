# Monrovia

###### Monrovia version 1.0.0
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/22007082/faf6f4e4-dc24-11e6-9731-f766c55500f0.png)

## Terminal Emulators

This repo includes [configuration files](terminal-colors) for using Monrovia in several terminal emulators, as well as a Vim/Neovim plugin. Please refer to your terminal emulator docs for info on how to use them.

## Vim

### 24 Bit Color Setup (Recommended)

If you have a GUI Vim or a 24-bit terminal with Vim 8 or Neovim, add this to your vimrc:

```VimL
set termguicolors
colorscheme Monrovia
```

Not sure if your terminal supports 24 bit colorschemes? Check out this list: [Truecolor Supported Terminals ](https://gist.github.com/XVilka/8346728)

### ANSI Setup

If you do not have Vim8 you can still run Monrovia in full color. You will need to use the Monrovia terminal theme in conjunction with the Monrovia.vim colorscheme. Essentially this method works similar to the Base-16 colorschemes in that vim will target the terminal colors ( 0 - 15 ). Then add this to your vimrc:

```VimL
colorscheme Monrovia
```

### Installation

You can use your vim package manager of choice to install monrovia 

There are a few ways to install Monrovia. The first option is by using your favorite vim package manager and the second is by manual download.

#### Via Package Manager

| Manager          | Location        | Setup                                                          |
|------------------|-----------------|----------------------------------------------------------------|
| Vundle           | add to .vimrc:  | `Plugin 'fuadsaud/Monrovia'`                                   |
| NeoBundle        | add to .vimrc:  | `NeoBundle 'fuadsaud/Monrovia'`                                |
| VimPlug          | add to .vimrc:  | `Plug 'fuadsaud/Monrovia'`                                     |
| Pathogen         | from terminal:  | `git clone https://github.com/fuadsaud/Monrovia ~/vim/bundle/` |

#### Manual Download

[Download the .zip](https://github.com/justinmk/vim-sneak/archive/master.zip) and copy `Monrovia.vim` to `~/.vim/colors` (on Windows `<your-vim-dir>\vimfiles\colors`). Or for global accessibility, `/usr/share/vim/vimfiles/colors`.

## Get in touch

Feedback, issues or suggestions?. Open an Issue [Monrovia Issues](https://github.com/fuadsaud/Monrovia/issues)!
