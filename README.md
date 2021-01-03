# picktheme

picktheme opens a Rofi menu displaying wallpapers found in $WALLPAPER\_DIR. When a wallpaper is selected, it will be set as background using feh, and a colorscheme will be applied using pywal. If $WALLPAPER\_DIR is not defined, the default directory is  $HOME/.config/wallpapers.

## Dependencies

- [rofi](https://github.com/davatorium/rofi)
- [pywal](https://github.com/dylanaraps/pywal)
- [feh](https://github.com/derf/feh)

## Installation

Clone this repository, then run `sudo make install`.
