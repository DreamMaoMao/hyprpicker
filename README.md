# hyprmag

A wlroots-compatible Wayland color picker that does not suck.

![hyprmagShort](https://user-images.githubusercontent.com/43317083/188224867-7d77a3b3-0a66-488c-8019-39b00060ab42.gif)

# Usage

Launch it. Click. That's it.

## Options

`-f | --format=[fmt]` specifies the output format (`cmyk`, `hex`, `rgb`, `hsl`, `hsv`)

`-n | --no-fancy` disables the "fancy" (aka. colored) outputting

`-h | --help` prints a help message

`-a | --autocopy` automatically copies the output to the clipboard (requires [wl-clipboard](https://github.com/bugaevc/wl-clipboard))

`-r | --render-inactive` render (freeze) inactive displays too

`-z | --no-zoom` disable the zoom lens

# Building

## Arch
`yay -S hyprmag-git`

## Manual
`make all`

the output binary is in `./build/hyprmag`

# Caveats

"Freezes" your displays when picking the color.
