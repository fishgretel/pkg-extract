[![](https://img.shields.io/badge/Wahoo-Package-00b0ff.svg?style=flat-square)][Wahoo]
![](https://img.shields.io/badge/License-MIT-707070.svg?style=flat-square)

# :collision: [_extract_](https://github.com/gretel/wa-extract)
> Extracts and expands a variety of archive files

extract development for [Wahoo][Wahoo] / [fish](fishshell.com).

## Install
> _Note_: You need to have the related tools installed prior to loading Wahoo.

On OSX you can use homebrew to install these:

```fish
brew install gnu-tar unrar xz
```

> GNU tar is kinda rare. Extraction will fail gracefully if you try to extract an according archive.

```fish
wa g extract
```

# License

[MIT](http://opensource.org/licenses/MIT) © [Tom Hensel][Author]

[Author]: https://github.com/gretel
[Wahoo]: https://github.com/bucaran/wahoo
