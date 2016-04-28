# 7guis-reflex

An implementation of the [7GUIs](https://github.com/eugenkiss/7guis/wiki) in [reflex-dom](https://hackage.haskell.org/package/reflex-dom).

## Build

You need to have [stack](http://docs.haskellstack.org/en/stable/README/) installed. Then:

    $ stack setup
    $ stack build

You may need to install some Haskell tools in order to boot GHCJS, for example `happy`. Use stack for that.

## Play

    $ google-chrome index.html
