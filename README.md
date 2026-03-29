# Kitty Themes

A collection of eye-friendly [kitty](https://sw.kovidgoyal.net/kitty/) terminal themes.

## Themes

| Theme | Type |
|-------|------|
| [komorebi.conf](komorebi.conf) | Light |
| [relax_light.conf](relax_light.conf) | Light |
| [relax_dark.conf](relax_dark.conf) | Dark |

## Install

```bash
cp *.conf ~/.config/kitty/themes/
```

Then either edit `kitty.conf`:

```
include themes/komorebi.conf
```

Or use the built-in theme picker:

```bash
kitty +kitten themes
```

## Contributing

Add a new `.conf` file following the existing format and update the table above.

## License

MIT
