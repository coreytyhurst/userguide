# Tyhurst Farmhouse Guide

Source for **[guide.tyhurstfarmhouse.com](https://guide.tyhurstfarmhouse.com)** — the user
guide for the *farm-cluster* home server. It helps friends and family use the apps and
services running on the Farmhouse: streaming, music, audiobooks, radio, retro games, D&D,
and more.

This is a simple, static documentation site. No accounts, no tracking, no fancy features —
just clear instructions.

## Built with

- [Hugo](https://gohugo.io/) — static site generator
- [hugo-book](https://github.com/alex-shpak/hugo-book) theme — vendored as a git submodule
- A custom "Farmhouse" design system in `assets/_custom.scss`

## Local development

You need **Hugo Extended `0.161.1`** (see [`.hugo-version`](.hugo-version) — the SCSS in
this site requires the *extended* build).

```bash
# Clone with the theme submodule
git clone --recurse-submodules https://github.com/coreytyhurst/userguide.git
cd userguide

# If you already cloned without --recurse-submodules:
git submodule update --init --recursive

# Run the dev server at http://localhost:1313
hugo server

# Production build (output in public/)
hugo --minify
```

## Repo layout

| Path | What's there |
|------|--------------|
| `content/`            | All guide pages (Markdown). `content/docs/` holds the service pages. |
| `assets/_custom.scss` | The Farmhouse design system — colors, typography, spacing. |
| `layouts/`            | Small theme overrides (e.g. Google Fonts injection). |
| `static/`             | Favicon and Open Graph image. |
| `themes/hugo-book/`   | The theme (git submodule — don't edit directly). |
| `hugo.yaml`           | Site configuration. |

## Deployment

Pushes to `main` are built and deployed automatically by **Cloudflare Pages**. Every pull
request is build-checked by GitHub Actions ([`.github/workflows/build.yml`](.github/workflows/build.yml))
so broken builds are caught before merge.

## Contributing

Spotted a mistake or have an idea? See [CONTRIBUTING.md](CONTRIBUTING.md). The quickest
path is to [open an issue](https://github.com/coreytyhurst/userguide/issues/new/choose).

## License

Content is licensed under [CC BY 4.0](LICENSE).
