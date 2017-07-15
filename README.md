# My Vim Configs
The configurations and files I use for my vim (actually GVim) setup. But, I will keep this public in case anyone wants to use them. If you don't mind, I'll give you a quick synopsis of each thing I use.

- **.vimrc:** My vim config file. Setup specifically for use with LaTeX and Python. Including shortcuts for things I use often.
- **Syntax:** It comes with syntax for Python and I have a LaTeX setup in `vim-live-latex-preview`.
- **Themeing:** There will be two vimrc files, both in seperate locations. One for my laptop (a ThinkPad X201 running Manjaro on Mate) and my desktop (a desktop a built myself running Manjaro Kde).

It is worth mentioning that I use [pathogen](https://github.com/tpope/vim-pathogen) as my script/package manager. So, before you use this, I would suggest that you install pathogen onto your computer. Also, the font I use, [anonymous pro](https://www.marksimonson.com/fonts/view/anonymous-pro), should be downloaded before you use this vimrc. Also, make sure that you have all of the appropriate color schemes. 

## TODO

* Include scripts to install things for people that are too lazy to install things.
* Create `autocmd` shortcuts for LaTex.
* Create `autocmd` shortcuts for Python.
* Create `.vimrc` for my laptop customized from the `.vimrc` on my desktop.

**A Quick Note:** I'm sorry I've been updating my `README` so much. I've been trying to see which desktops and distros I like. While I'm certain Manjaro is fantastic for my desktop computer, I need to find distros that can support lighter hardware and support my needs. More specifically 
  * The AUR
  * Easy [Sagemath](https://github.com/sagemath/sage) & [Jupyter](https://github.com/jupyter/notebook) integration[\*]
  * Light system usage
  * Only prepackaged with critical or useful software (like including a PDF viewer but not a full office suite).
  
  #### Notes
  ___
  
  [\*] It makes math, physics, and data analysis *much* easier compared to either the console or terminal versions. Also, most CASs like [Giac](https://www-fourier.ujf-grenoble.fr/~parisse/giac.html) or [REDUCE](http://reduce-algebra.sourceforge.net/) are either far too spcialized or far too general to use for my purposes. 
