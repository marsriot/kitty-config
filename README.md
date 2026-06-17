# kitty-config

My personal [kitty](https://sw.kovidgoyal.net/kitty/) terminal configuration.

## Theme

Matrix-inspired hacker aesthetic — black background, neon green (`#00ff41`) foreground, with a full 16-color palette tuned for contrast.

## Features

- **Font:** JetBrains Mono, 12pt
- **Tabs:** Powerline style, docked to the bottom
- **Opacity:** 85% background transparency with dynamic opacity support
- **Scrollback:** 10,000 lines
- **Copy on select** enabled

## Keybindings

| Shortcut | Action |
|---|---|
| `Ctrl+T` | New tab |
| `Ctrl+Shift+W` | Close tab |
| `Ctrl+Shift+]` | Next tab |
| `Ctrl+Shift+[` | Previous tab |
| `Ctrl+Shift+Enter` | New window |
| `Ctrl+=` | Increase font size |
| `Ctrl+-` | Decrease font size |
| `Ctrl+C` / `Ctrl+Shift+C` | Copy to clipboard |
| `Ctrl+V` / `Ctrl+Shift+V` | Paste from clipboard |

## Install

```bash
cp kitty.conf ~/.config/kitty/kitty.conf
```

Requires [JetBrains Mono](https://www.jetbrains.com/lp/mono/) — or swap `font_family` for `monospace` to use your system default.
