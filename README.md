
    $vfv/packs/packs-cp/opt/vim-gfm-syntax/README.md

My fork of [rhysd/vim-gfm-syntax](https://github.com/rhysd/vim-gfm-syntax) with thanks to the developers.

## explanation
This plugin is dated - preservim's markdown plugin is much better - see my clone [vim-markdown](https://github.com/harriott/vim-markdown).

Nevertheless, this plugin has a few small advantages, and I keep this fork just for

- correctly highlighting some gfm files such as [$DCGRs/unix/neomutt-neomutt/contrib/oauth2/README.md](https://github.com/neomutt/neomutt/blob/main/contrib/oauth2/README.md)
- highlighting emojis (see [$vfv/plugin/packsFull.vim](https://github.com/harriott/vimfiles/blob/master/vim/plugin/packsFull.vim))

The two (this and preservim's) don't play well together, so this fork, along with my configurations (see [$vimfiles/ftplugin/gfm.vim](https://github.com/harriott/vimfiles/blob/master/ftplugin/gfm.vim)) allows me to use this plugin exclusively for `*.gfm` files.

Other than this brief README, the only significant change in this fork is that `vim-gfm-syntax/after/syntax/markdown/` is renamed to `vim-gfm-syntax/after/syntax/gfm/`.

I've also removed rhysd's test kit.

