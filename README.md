# perl1line.txt for navi

## *Credit*

### *perl1line.txt*

This is a customization of [Peteris Krumins's](http://www.catonmat.net/)   collection of handy perl one-liner scripts, [https://github.com/pkrumins/perl1line.txt](https://github.com/pkrumins/perl1line.txt)

In my repo, in the master branch, the original oneliner scripts have not been changed in any way.

If you are interested in the original, please go to the repository where I have forked this repo from, [https://github.com/pkrumins/perl1line.txt](https://github.com/pkrumins/perl1line.txt).

### *navi*

See [denisidoro/navi](https://github.com/denisidoro/navi): An interactive cheatsheet tool for the command-line.

## *Description*

My customizations of `perl1line.txt` are in the branch `navi-cheatsheet`.

There I have renamed `perl1line.txt` to `navi-perl1line-cheatsheet.cheat` and added some comments. Some redundant or alternative Oneliners might have been removed, added or tweaked with (Work in Progress).

The cheatsheet syntax that `navi` requires  is documented [in the navi repo](https://github.com/denisidoro/navi/blob/master/docs/cheatsheet_syntax.md).

## *Why this fork?*

The file `perl1line.txt` is already in the correct format, *almost*. It just needed some additional special-purpose comments, to give it a topical substructure that `navi` can display in its user interface, opened with `CTRL+G`.

In a terminal window, the GUI of `navi` looks like this:

![Userinterface of navi-cheatsheet](./userinterface--navi-cheatsheet-tool--perl-oneliners.png)

- works for me.
- **(To be continued)**

## Installation

Roughly, the following steps are required:

- play with [https://cheat.sh](https://cheat.sh), see its [Github repo](https://github.com/chubin/cheat.sh), and perhaps install the command-line-client [cht.sh](https://github.com/chubin/cheat.sh#command-line-client-chtsh)
- On Linux, install command-line tools `navi` and its dependency `fzf`, the fuzzy-finder
- `git clone` this repo, and switch into branch `navi-cheatsheet`.
- Copy the perl1line.cheat file from this repo into navi's cheatsheet directory.
