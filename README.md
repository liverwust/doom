# dotvim

My .doom.d files for [Doom Emacs](https://github.com/doomemacs/doomemacs)

## license

MIT. See LICENSE.txt.

# Bootstrapping

This repo uses [homeshick](https://github.com/andsens/homeshick). The
sequence for accessing the configs on a new machine is:

1. git clone git://github.com/andsens/homeshick.git $HOME/.homesick/repos/homeshick
2. source $HOME/.homesick/repos/homeshick/homeshick.sh
3. homeshick clone liverwust/doom
4. respond "y" or "n" (see below) when prompted about symlinking
