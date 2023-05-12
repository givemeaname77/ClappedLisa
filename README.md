# ClappedLisa Nerd Fonts

_Patched on: 2023-04-17 08:41_.

## Setup

You can copy all the fonts to your system's fonts directory, either **~/.fonts/** or **~/.local/share/fonts/**.

```sh
git clone https://github.com/givemeaname77/ClappedLisa.git
cd ClappedLisa.git
mkdir -p ~/.fonts
cp ./patched/* ~/.fonts/
```

Verify if the fonts are installed correctly.

```sh
fc-list | grep "ClappedLisa"
```

Here is my *alacritty* config example to use ClappedLisa font.

```yaml
# Font configuration
font:
  size: 12
  offset:
    x: 0
    y: 0
  glyph_offset:
    x: 0
    y: 0
  normal:
    family: ClappedLisa Nerd Font
    style: Regular
  bold:
    family: ClappedLisa Nerd Font
  italic:
    family: ClappedLisa Nerd Font

```

**Happy typing !**

MonoLisa nerd fonts patched with _font_patcher_, with glyphs and symbols. Includes following fonts.

- ClappedLisa-BlackItalic.ttf
- ClappedLisa-Light.ttf
- ClappedLisa-Black.ttf
- ClappedLisa-MediumItalic.ttf
- ClappedLisa-BoldItalic.ttf
- ClappedLisa-Medium.ttf
- ClappedLisa-Bold.ttf
- ClappedLisa-RegularItalic.ttf
- ClappedLisa-ExtraLightItalic.ttf
- ClappedLisa-Regular.ttf
- ClappedLisa-ExtraLight.ttf
- ClappedLisa-ThinItalic.ttf
- ClappedLisa-LightItalic.ttf
- ClappedLisa-Thin.ttf

## References

Make sure to install all the dependencies. Patched on debain (Pop OS).

- [Nerd Font Patcher](https://github.com/ryanoasis/nerd-fonts#font-patcher).
