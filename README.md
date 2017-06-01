Dotfiles
========

A bunch of configuration files for editors and other UNIX tools.

Installation
------------

Then install the dotfiles:

    $ cd ~/.dotfiles
    $ make help        # Show help message
    $ make install     # Create symblinks
    $ make deps        # Optional install system dependences like 'ctags' and 'pycscope', require root privilege
    $ make uninstall   # Restore backups and remove symblinks

It will backup existing files as `<file>.dotfiles.bak`.

The dotfiles will be symlinked, e.g. `~/.bashrc` symlinked to `~/.dotfiles/dotfiles/bashrc`.
