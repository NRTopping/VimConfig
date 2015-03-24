VimConfig (Mac OSX)
===================

Vim Configuration Files and plugins for vim/macvim. You will need to install <a
href="https://github.com/b4winckler/macvim">macvim</a> in order to make the most
of these pluggins. I suggest installing it with <a
href="http://brew.sh/">Homebrew</a> in order to streamline the process.

To Use
======
You will need to clone this git repository to your ~/.vim directory. Once you
have done that, create a link between ~/.vim/.vimrc and ~/.vimrc. 

Current Plugins 
===============
<a href="https://github.com/tpope/vim-pathogen">Pathogen</a> - Plugin manager
for vim.

<a href="https://github.com/Valloric/YouCompleteMe">YouCompleteMe</a> - Code completion engine for vim, uses clang to provide sytnax/auto-completion for c languages. 

<a href="https://github.com/powerline/powerline">Powerline</a> - Provides more information in the statusline (makes it look nicer as well) 

<a href="http://eclim.org/">Eclim</a> - Allows you to make eclipse projects entirely in terminal and use VI to edit the files (resides in /Applications/eclipse). 

<a href="https://github.com/Raimondi/delimitMate">delimitMate</a> - provides
insert mode auto-completion for quotes, parens, brackets, etc.

<a href="https://github.com/marijnh/tern_for_vim">Tern For Vim</a> - Provides
tern based JavaScript Editing support

<a href="https://github.com/vim-scripts/closetag.vim">CloseTag</a> - Provides
autocompletion for html closing tags after typing &lt;/

<a href="https://github.com/scrooloose/nerdcommenter">NerdCommenter</a> -
Provides ability to quickly comment and uncomment lines (<#>\ci)

<a href="https://github.com/tpope/vim-fugitive">Fugitive</a> - Awesome git
support in vim, see these <a
href="http://vimcasts.org/blog/2011/05/the-fugitive-series/">screencasts</a> for tutorials.

<a href="https://github.com/majutsushi/tagbar">Tagbar</a> - Provides easy way to
browse tags of the current file, creates sidebar and displays ctags. I.e.
displays function definitions for a C/C++ file. Need to install Exuberant ctags
(brew install ctags-exuberant).

<a href="https://github.com/altercation/vim-colors-solarized">Solarized</a> - Dem colors

<a href="https://github.com/scrooloose/nerdtree">NerdTree</a> - provides easy access to folders


Helpful Aliases 
===============
alias vi="mvim -v"

alias eclim='/Applications/eclipse/eclimd'
