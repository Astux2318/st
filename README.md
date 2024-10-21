# My build of st

st with a few patches added to it:

- Transparency
- Improved box drawing and glyph rendering
- External pipe
- Support for multiple fonts
- Wide glyph support
- Scrollback (with `ctrl+shift+j` and `ctrl+shift+k`)
- Ligature support

## Other things

My build of st also uses the gruvbox colorscheme by default, but can be changed
at compile time.

## Install

To install make sure that you have xlib and harfbuzz installed.

```
cd st
sudo make install
```
