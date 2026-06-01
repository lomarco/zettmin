---
title: Home
date: 2026-05-14
tags: note
---

# Zettmin

_**Zettmin**_ is a minimalist Hugo theme by [lomarco](https://github.com/lomarco) for Zettelkasten-style "second brain" or digital garden sites that does not require JavaScript. It supports wikilinks rendering, backlink lists, tag and category indexes, and more.

Zettmin consists of about 350 lines of HTML and CSS:
``` bash
find . -not -path '*/exampleSite/*' \( -name '*.html' -o -name '*.css' \) | xargs wc -l
```

``` plain
  127 ./assets/css/main.css
    5 ./layouts/section.html
   13 ./layouts/page.html
    9 ./layouts/_partials/files.html
   15 ./layouts/_partials/head/css.html
    4 ./layouts/_partials/head.html
   42 ./layouts/_partials/menu.html
    1 ./layouts/_partials/header.html
    3 ./layouts/_partials/footer.html
   46 ./layouts/_partials/wikilinks.html
   38 ./layouts/_partials/backlinks.html
   23 ./layouts/_partials/terms.html
   17 ./layouts/baseof.html
    5 ./layouts/404.html
    5 ./layouts/term.html
    9 ./layouts/taxonomy.html
    4 ./layouts/home.html
   10 ./layouts/categories/list.html
   12 ./layouts/shortcodes/image.html
   12 ./layouts/shortcodes/video.html
  400 total
```

`$${\sqrt {n}}\left(\left({\frac {1}{n}}\sum _{i=1}^{n}X_{i}\right)-\mu \right)\ {\xrightarrow {d}}\ N\left(0,\sigma ^{2}\right)$$`

For instructions on using this theme, see [[start_guide]].
