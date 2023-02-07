
My fork of [rhysd/vim-gfm-syntax](https://github.com/rhysd/vim-gfm-syntax) with thanks to the developers.

## explanation
This plugin is dated - preservim's markdown plugin is much better - see my clone [vim-markdown](https://github.com/harriott/vim-markdown).

Nevertheless, this plugin has a few small advantages, and I keep this fork just for being able to syntax highlight emojis.

The two don't play well together, so this fork, along with my configurations (see [$vimfiles/ftplugin/gfm.vim]()) allows this plugin to be used exclusively for `*.gfm` files.

Other than this brief README, the only significant change in this fork is that `vim-gfm-syntax/after/syntax/markdown/` is renamed to `vim-gfm-syntax/after/syntax/gfm/`.

I've also removed rhysd's test kit.

