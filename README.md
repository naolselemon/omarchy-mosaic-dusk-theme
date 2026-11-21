# Mosaic Dusk

An Omarchy theme drawn from the [Mosaic](https://github.com/naolselemon/mosaic) artwork: deep slate and evergreen, muted sea-glass accents, and warm light at the edge of night.

![Mosaic Dusk on Omarchy](preview.webp)

Install from this repository and cycle through its six backgrounds:

```sh
omarchy theme install https://github.com/naolselemon/omarchy-mosaic-dusk-theme.git
omarchy theme bg next
```

The starting background, **Mosaic Midpoint**, is joined by five companion scenes (WebP/PNG wallpapers in `backgrounds/`, editable SVG artwork in `artwork/`):

- **First Light** — dawn breaking through a mountain pass over still water.
- **Cascades** — water finding its way through fractured stone.
- **Stillpoint** — a mountain held in the reflection of a quiet tarn.
- **Cloud Sea** — ridges rising above a basin of mist.
- **Night Pines** — moonlight falling across the water and dark firs.

## GTK file managers and apps

`colors.toml` themes Omarchy's supported apps; `icons.theme` selects sage-colored GNOME icons. Omarchy does not automatically load custom GTK palette CSS from an installed theme.

For matching GTK3/GTK4 backgrounds and a teal accent, see the [separate, opt-in GTK integration](https://github.com/naolselemon/omarchy-mosaic-dusk-gtk-integration). The GTK files here are color-only stylesheets (`gtk-3.0.css` and `gtk-4.0.css`); the executable hook belongs to the companion repository. Reopen running GTK apps to pick up their stylesheet; other toolkits require their own theme support.

The preserved [original Mosaic wallpaper source](https://github.com/naolselemon/mosaic/blob/main/assets/showcase-wallpaper.svg) lives in the Mosaic repository rather than being duplicated here. Artwork and theme © 2026 Naol Selemon; licensed under the MIT License (see [LICENSE](LICENSE)).
