# "Mutenight Scene" Theme for Vim

Example within a C++ document:

![drag](https://i.imgur.com/O5J0VEI.png)

Example within an HTML file:

![drag](https://i.imgur.com/YTWw38i.png)

---
**Important**
This theme's colors were chosen with 256-bit color in mind. Although it
will sort've work with lower thresholds, it wasn't designed for it.

## Installation

**Vim Plug or other plugin managers:**
Open your `vim.rc` files, and within the area of adding plugins, add

`Plug: 'HenryNewcomer/vim-theme-mutenight_scene'`.

Now scroll down past the `plug#end()` area and add:

    colorscheme mutenight_scene
    set background=dark
    syntax on

If using another plugin manager, such as Vundle, the steps are appropriately
similar for the first part. The second part is the same. Just reference your
plugin manager's manual for further assistance on what syntax to use for
automatically installing plugins.

## Manual Installation
Linux/Mac OS) If on a Unix-based OS, simply clone/save this and place it in your
 `~/.vim/colors/` directory (assuming you haven't changed this path).

Next, open, your `.vimrc` file and add:

    colorscheme mutenight_scene
    set background=dark
    syntax on

Note that if you have a plugin manager and are using the manual installation,
you will most likely have to add the three commands *after* your plugin's closing
method. For example, if using Vim Plug, you'd add the lines after `plug#end()`.

---

<<<<<<< HEAD
Feel free to check out my other themes:
+ https://github.com/HenryNewcomer/vim-theme-papaya
+ https://github.com/HenryNewcomer/vim-theme-underflow

---
=======
Todo: Update the 8-bit color representations so they correspond with with the hex
colors.
>>>>>>> 29ccdf05484f3cb5d0dcfdc42cc534bf117bae31

I haven't tested this theme using every language that Vim supports, but most of
the more popular ones should look good. If you notice any oddities or have any
questions, feel free to e-mail me at a.cliche.email@gmail.com

*This project is licensed under the MIT License. Feel free to use and distribute
it.*
