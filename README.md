# Sanctuary: an Omarchy theme

Dark green and turquoise, with traditional Catholic churches as wallpapers.

## Install

1. Copy this folder to `~/.config/omarchy/themes/sanctuary`
2. Run `omarchy-theme-set sanctuary`
3. Cycle wallpapers with `omarchy-theme-bg-next`

## The six wallpapers (in `backgrounds/`)

| # | Subject | Type |
|---|---------|------|
| 1 | Stained-glass window with light rays | Interior |
| 2 | Notre-Dame de Paris, portal sculpture | Exterior |
| 3 | Santa Maria della Salute, Venice | Exterior |
| 4 | Siena Cathedral | Exterior |
| 5 | St. Peter's Basilica, dome and baldachin | Interior |
| 6 | St. Peter's Basilica, from Via della Conciliazione | Exterior |

All six are graded to a dark-green to turquoise two-tone look at 2560x1440.

## Regrading or swapping photos

```
tools/grade-wallpapers.sh ~/Pictures/churches
MODE=tint tools/grade-wallpapers.sh ~/Pictures/churches
```

The default `duotone` mode gives the full dark-green to turquoise look.
`tint` keeps more of each photo's own colors, shifted toward green and teal.
Results are written to `backgrounds/`. Delete the files you don't want there
first, since the script only adds or overwrites. Needs ImageMagick.

Check the license of each source photo before sharing the theme publicly.

## Palette

| Role | Color |
|------|-------|
| Background | `#0a1a17` |
| Foreground | `#cfe8e3` |
| Accent | `#2dd4bf` |
| Bright accent | `#7ff0df` |

## Included

`colors.toml` (drives the terminal, bar, launcher, borders and lock screen),
`btop.theme`, `chromium.theme`, `icons.theme` (Yaru-viridian).
