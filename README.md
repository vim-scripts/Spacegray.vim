# Spacegray.vim

Spacegray is a colorscheme for Vim loosely modeled after
the [spacegray](https://github.com/zdne/spacegray-xcode) theme for Xcode.

## Screenshots

Here are a few screenshots of Spacegray:

### C

![Spacegray in C](http://cl.ly/Yxcd/C-spacegray.png)

### JavaScript
![Spacegray in JavaScript](http://cl.ly/Yx75/JS-Spacegray.png)

### Vim
![Spacegray in Vim](http://cl.ly/Yxfr/vim-spacegray.png)

## Installation

If you don't have a preferred installation method, I recommend installing
[pathogen.vim](https://github.com/tpope/vim-pathogen), and then simply copy and
paste:

    cd ~/.vim/bundle && git clone git://github.com/ajh17/Spacegray.vim.git

Then in your ~/.vimrc, add this line:

    colorscheme spacegray

## Terminal Environment

If you use Spacegray inside a Terminal, please make sure you use a Terminal
with 256 color support. Most these days are. Ensure that the default TERM
contains the string `256color`. An example would be `xterm-256color` or
if using tmux or screen, `screen-256color`.

### Terminal Color Palette

Spacegray will look good in a dark terminal colorscheme, but if you use
Spacegray's color palette, it will look beautiful.

### iTerm2

If you use iTerm2, Spacegray.itemcolors is provided with the download.

### Terminator

For terminator users, Spacegray.terminator is provided and can be installed by
copying to `~/.config/terminator/config` on Linux or `$XDG_CONFIG_HOME/terminator/config`
if you're running OS X.

### Xresources

For Linux/BSD users, here is a sample ~/.Xresources:

    *background: #111314
    *foreground: #B7BBB7
    ! black
    *color0: #2C2F33
    *color8: #4B5056
    ! red
    *color1: #B04C50
    *color9: #B04C50
    ! green
    *color2: #919652
    *color10: #94985B
    ! yellow
    *color3: #E2995C
    *color11: #E2995C
    ! blue
    *color4: #66899D
    *color12: #66899D
    ! magenta
    *color5: #8D6494
    *color13: #8D6494
    ! cyan
    *color6: #527C77
    *color14: #527C77
    ! white
    *color7: #606360
    *color15: #DDE3DC
