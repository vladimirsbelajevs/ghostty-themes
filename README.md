# Everforest themes for Ghostty

Two dark [Everforest](https://github.com/sainnhe/everforest) color schemes for the [Ghostty](https://ghostty.org/) terminal emulator.

## Included themes

| Theme | Background |
| --- | --- |
| `Everforest_dark_medium` | `#2d353b` |
| `Everforest_dark_soft` | `#333c43` |

## Installation

Clone the repository and copy the theme files into Ghostty's user theme directory:

```sh
git clone https://github.com/vladimirsbelajevs/ghostty-themes.git
mkdir -p ~/.config/ghostty/themes
cp ghostty-themes/Everforest_dark_* ~/.config/ghostty/themes/
```

Alternatively, download either theme file from this repository and place it in `~/.config/ghostty/themes/`.

## Usage

Set one of the installed themes in `~/.config/ghostty/config`:

```ini
theme = Everforest_dark_medium
```

To use the softer background instead:

```ini
theme = Everforest_dark_soft
```

Reload Ghostty's configuration or restart Ghostty for the change to take effect.

## License

This project is available under the [MIT License](LICENSE).
