# Wilted

Warm syntax themes with muted colors to lessen visual clutter.

## Installation

Install with your favorite package manager and add the following to your vimrc:

```
syntax enable       " enable syntax highlighting.
set termguicolors   " enable true color support.
colorscheme wilted  " set the colorscheme to wilted.
```

The `background` setting has no effect, since a dark mode is not supported.

--- 

Add the following snippet to your vimrc if colors aren't displayed correctly:

```
execute "set t_8f=\e[38;2;%lu;%lu;%lum"
execute "set t_8b=\e[48;2;%lu;%lu;%lum"
```

## Configuration

Palettes can be configured using `g:wilted#palette`. Wilted uses `bouquet` by
default, which features a full range of colors. The other palettes available
are dichromatic.

Example:

```
let g:wilted#palette = 'fuchsia'
colorscheme wilted
```

Available palettes: `bouquet, fuchsia, chicory`

## Screenshots

### Bouquet

![Bouquet](https://i.imgur.com/mlUAJWD.png)

### Fuchsia

![Fuchsia](https://i.imgur.com/qpXlyp6.png)

### Chicory

![Chicory](https://i.imgur.com/vT9pdNJ.png)

## License

[CC0 1.0 Universal (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/)
