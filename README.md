# config.ghostty

My personal configuration for [Ghostty](https://ghostty.dev), the terminal emulator built on top of [libghostty](https://github.com/ghostty-org/libghostty).

## Files

- `config` — Ghostty configuration file. Copy it to your Ghostty config directory (e.g. `~/.config/ghostty/config`) or symlink it.

## Usage

```sh
# Symlink into Ghostty's config location
ln -s ~/Projects/config.ghostty/config ~/.config/ghostty/config
```

## Configuration highlights

- **Theme**: TokyoNight with transparent background and blur
- **Font**: JetBrainsMono Nerd Font at 11pt, thickened
- **Cursor**: block style, no blink
- **Shell**: fish with shell integration auto-detected
- **Terminal**: clipboard access enabled, copy-on-select, 10k line scrollback

## License

MIT — see [LICENSE](LICENSE).