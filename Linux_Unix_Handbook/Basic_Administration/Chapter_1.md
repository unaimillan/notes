# Basic Introduction

## Interactive documentation

Mainly `man [SECTION] PAGE` with using `less` program as in *PAGER* env. variable. There also exist old and legacy `info` system.

Man stores pages in `/usr/share/man` compressed and un`gzip` them on the fly.

TODO: here should be table of man sections

## Useful search commands

This commands helps to find things:

- `which` to find a relevant binary in `$path`
- `whereis` just broader range of search
- `locate` uses precompiled index of filesystem to match pattern

The filesystem index DB can be updated with `updatedb`
