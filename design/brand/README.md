# Atelier — brand

A plumb bob hung true inside a ring. Ink first; brass marks the bob and nothing else.

The direction was named Plumb when it was chosen. The editable source is the
Claude Design project this kit was exported from: changes are made there and
exported again, never made to these files by hand.

## What's here

| Folder | Contents |
|---|---|
| `logo/mark` | The mark. `-small` is the cut for 24 px and below (heavier ring and line). |
| `logo/wordmark` | `atelier` outlined from Hanken Grotesk Light. `-small` is Regular, for 24 px and below. |
| `logo/lockup` | Mark + wordmark, plus 2× PNGs for places that won't take SVG. |
| `logo/family/<part>` | `atelier`, the bob, then the part name — text-only, and `-lockup` with the mark. Gauge, Insights, Registry, Box. Registry and Box assume the parts' names are aligned under Atelier, which is not yet decided. |
| `app-icon/hicolor` | Linux icon theme layout: PNG 16–512, `scalable/` SVG, `symbolic/` for GNOME. |
| `app-icon/src` | The three tile cuts the PNGs were rendered from (full ≥64, mid 32–48, tiny ≤24). |
| `favicon` | `favicon.svg` (switches with the colour scheme), `favicon.ico` (16/32/48), touch and manifest PNGs. |
| `glyphs` | The five role glyphs, `currentColor`, 1.5 stroke on 24. `sprite.svg` holds all five as `<symbol>`s. |
| `social` | 1280×640 GitHub social preview, light and dark. |
| `tokens` | Colours and type as CSS custom properties and JSON. |

Every logo comes in `light` (ink + brass, for light grounds), `dark` (paper + light brass, for dark grounds), `black` and `white`.

## Principles

- **One colour first.** The mark has to work in `black`/`white` before it works in brass.
- **Small cut under 24 px.** The thin ring breaks up below that; use `-small` files.
- **Clear space** around any logo: the height of the bob, at the size used.
- **Parts never get their own mark.** A part is `atelier`, the bob, then its name in medium weight.
- **No ▼ in the product.** Show regressions as signed numbers or words, so nothing competes with the bob.

## Usage

GitHub README header (follows the viewer's theme):

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="design/brand/logo/lockup/atelier-lockup-dark.svg">
  <img alt="atelier" src="design/brand/logo/lockup/atelier-lockup-light.svg" height="56">
</picture>
```

Web favicon:

```html
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="icon" href="/favicon.ico" sizes="48x48">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
```

Linux desktop app: copy `app-icon/hicolor` into `/usr/share/icons/hicolor` (or `~/.local/share/icons/hicolor`), set `Icon=atelier` in the `.desktop` file, then `gtk-update-icon-cache`.

Terminal: the brand is `⊥` in the accent colour (ANSI 256: 179 on dark, 94 on light).

## Type

Hanken Grotesk 300 / 400 / 500 for headings and body; IBM Plex Mono for code and the terminal. Both are SIL Open Font License; the wordmark is outlined, so the font isn't needed to display the logo.

## Colour

| Token | Light | Dark |
|---|---|---|
| ground | `#F4F4F2` | `#121210` |
| surface | `#FFFFFF` | `#1B1A17` |
| rule | `#D9D7D1` | `#322F2A` |
| muted | `#5E5B54` | `#A49F95` |
| ink | `#1A1916` | `#EDEAE3` |
| accent (brass) | `#7A5A12` | `#D4AE5C` |
