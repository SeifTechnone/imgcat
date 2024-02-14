# Command imgcat displaying images in Termux
Termux can display images and gifs using sixel and iterm2 protocols.

## Requires
+ [Termux Monet](https://github.com/KitsunedFox/termux-monet/releases)

## Features
+ One command setup
---
## How to use
For displaying images and gifs using `Sixel`, do Type this command
```shell
pkg install libsixel
```
and use `img2sixel image.png`
---
For displaying images using `iTerm2`, do Type this command in Termux Monet
```shell
source <(curl -fsSL https://raw.githubusercontent.com/SeifTechnone/imgcat/main/imgcat.sh)
```
and use it with the command `imgcat image.png`