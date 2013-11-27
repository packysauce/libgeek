Quick Start
===========
1. $ git clone https://github.com/patrickdwhite/libgeek.git ~/.libgeek
2. Add 'export LIBGEEK=~/.libgeek' to your .bashrc or .zshrc (or whatever rc file you use)

Extra Info
==========
libs are handy functions that everybody can use
plugins are specific doodads that make use of plugins

Example
=======
Here's an example NerdTool command to list the spotify artist
(doesn't require modifying any rc file)

    export LIBGEEK=~/.libgeek
    $LIBGEEK/libgeek spotify artist

If you did modify your rc file, it won't take effect in NerdTool until you 
log out and back in. If you do it exactly like the above, it should work
