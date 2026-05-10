# Zettmin — minimalistic Zettelkasten Hugo theme

**Zettmin** — a minimal theme for [Hugo](https://gohugo.io) suitable for blogs, a second brain (Obsidian-like), digital gardens, and more.

[photo]

## Features
- Wikilinks support: link by internal `title = "Title example"`, by filename, and bracketed links in the form `[[note_title|text]]`.
- Backlinks list support.
- Tag index.
- Sections (directories) list.
- Minimalist design.
- No JavaScript.
- Under 300 lines of HTML.


## Quick start
1. Install the theme as a git submodule or copy the theme directory into `themes/zettmin`:
```bash
git submodule add https://github.com/lomarco/zettmin themes/zettmin
```

2. In the root of your Hugo site, enable the theme in `config.toml`:
```
theme = "zettmin"
```

3. (Optional) Copy the contents of `themes/zettmin/hugo.toml` into your own `hugo.toml` for further customization.

## License
Zettmin is licensed under the MIT License. See the [LICENSE](LICENSE) for details.
