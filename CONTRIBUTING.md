# Contributing

Thanks for helping make the Farmhouse guide better. This is a small, friendly project —
contributions of any size are welcome.

## For Farmhouse users

You don't need to know Git or Hugo to help. If something in the guide is wrong, confusing,
or missing, the easiest path is to
[open an issue](https://github.com/coreytyhurst/userguide/issues/new/choose):

- **Content correction** — something is inaccurate or out of date.
- **Content suggestion** — a new page or section would help.

For account requests, login problems, or server issues, email the admin directly at
**coreytyhurst@gmail.com** — don't file a public issue for those.

## Editing content

Guide pages live in `content/docs/` as Markdown files. To preview changes locally, see the
setup steps in the [README](README.md#local-development), then run `hugo server`.

Each page starts with frontmatter:

```yaml
---
title: "Page Title"
weight: 30
---
```

- `title` — shown in the sidebar and browser tab.
- `weight` — controls sidebar order (lower appears first).

Link to other guide pages with a `relref` shortcode rather than a hard-coded URL:

```markdown
See [Troubleshooting]({{< relref "/docs/troubleshooting" >}}) for fixes.
```

### Style guide

Match the voice of the existing pages:

- **Pithy** — short sentences, no filler. Say it once, clearly.
- **Friendly** — warm and welcoming, written for non-technical readers.
- **Second person** — address the reader as "you."
- Prefer numbered steps and short lists over long paragraphs.
- Be honest about limitations instead of overpromising.

## Commits and pull requests

- This repo uses [Conventional Commits](https://www.conventionalcommits.org/) — e.g.
  `feat:`, `fix:`, `docs:`, `chore:`.
- Make sure the site builds locally (`hugo`) with no errors before opening a PR. CI runs
  the same check on every pull request.
- For visual changes, include a screenshot in the PR description.

## Changelog

Notable repo changes are recorded in [CHANGELOG.md](CHANGELOG.md). It tracks *releases of
this repository* and is separate from the in-site **Announcements** page, which is for
server news aimed at users.
