[![](https://img.shields.io/badge/Wahoo-Package-00b0ff.svg?style=flat-square)][Wahoo]
![](https://img.shields.io/badge/License-MIT-707070.svg?style=flat-square)

# :collision: [_extract_](https://github.com/gretel/wa-extract)
> Extracts and expands a variety of archive files

extract development for [Wahoo][Wahoo] / [fish](fishshell.com).

## Install
> _Note_: You need to have the related tools installed prior to loading Wahoo.

> Unzip, bzip2, (bsd)tar and pax come with OSX.
> More recent versions of these can be installed using `homebrew`.

Unrar and the (recommendable) XZ can easily be installed on OSX:

```fish
brew install unrar xz
```

> GNU tar is kinda rare. Extraction will fail gracefully if you try to extract an according archive.
If required on OSX you can install it using `homebrew`, too:

```fish
brew install gnu-tar
```

Finally, add the package to Wahoo:

```fish
wa g extract
```

# License

[MIT](http://opensource.org/licenses/MIT) © [Tom Hensel][Author]

[Author]: https://github.com/gretel
[Wahoo]: https://github.com/bucaran/wahoo
