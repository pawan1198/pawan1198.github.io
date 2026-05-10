# Awesome ggplot2 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated, searchable resource hub for R data visualization with ggplot2.
> Live site → **[pawan1198.github.io](https://pawan1198.github.io)**

---

## What's Inside

| Category | Count |
|---|---|
| R Packages | 120+ |
| Text Tutorials | 40+ |
| Video Tutorials | 4 |
| Books | 4 |
| Key Authors | 9 |
| Galleries | 3 |

---

## Site Features

- **Live search** — filters all resources instantly as you type
- **Category tabs** — jump to Packages / Tutorials / Books / Spatial / Themes / People
- **Sticky TOC** — always-visible table of contents with active-section highlighting
- **Scroll animations** — cards animate in as you scroll
- **Dark terminal aesthetic** — clean, readable, low-eyestrain design
- **Zero dependencies** — pure HTML/CSS/JS, no framework, no build step

---

## Package Categories

- **Geometrics** — calendR, ggbump, ggridges, ggstream, ggrepel, ggtree, ggwaffle, and 30+ more
- **Themes & Aesthetics** — ggthemes, hrbrthemes, ggsci, paletteer, ggdark, ggtext, and more
- **Presentation & Composition** — patchwork, cowplot, gganimate, ggforce, ggiraph, plotly
- **Spatial & Maps** — ggmap, ggspatial, rayshader, ggOceanMaps, urbnmapr
- **Icons, Patterns & Images** — ggpattern, ggimage, ggflags, emoGG
- **Data & Statistical Models** — GGally, ggstatsplot, tidybayes, survminer, naniar, ggeffects

---

## Repository Structure

```
pawan1198.github.io/
├── index.html          # Main site — standalone, no build required
├── _config.yml         # Jekyll config (disables old theme, serves index.html)
├── README.md           # This file
└── r-cheatsheets/      # Git submodule — R cheatsheet collection
```

---

## Contributing

Contributions welcome! To add a package, tutorial, or resource:

1. Fork this repository
2. Open `index.html`
3. Find the relevant `<div class="subsection">` section
4. Add a new `<div class="card">` following the existing pattern:

```html
<div class="card" data-search="keywords for search">
  <p class="card-pkg"><a href="PACKAGE_URL" target="_blank">{packageName}</a></p>
  <p class="card-desc">Short description of what the package does.</p>
</div>
```

5. Submit a pull request

For tutorials or books, add a `<li>` to the relevant `<ul class="resource-list">`.

---

## Related

- [Awesome R](https://awesome-r.com/) — broader R ecosystem list
- [ggplot2 Extensions Gallery](https://exts.ggplot2.tidyverse.org/) — official extension index
- [The R Graph Gallery](https://www.r-graph-gallery.com/) — chart recipes with R code

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Pawan](https://github.com/pawan1198) has waived all copyright and related rights to this work.
