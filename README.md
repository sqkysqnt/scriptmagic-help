# ScriptMagic Help

Documentation site for [ScriptMagic](https://scriptmagic.app) — a collaborative platform for script markup, rehearsal planning, and show preparation.

**Live site:** [help.scriptmagic.app](https://help.scriptmagic.app)

## About

This repository contains the source files for the ScriptMagic help center. The site is built with [MkDocs](https://www.mkdocs.org/) using the [Material for MkDocs](https://squidfundamentals.github.io/mkdocs-material/) theme and deployed to GitHub Pages.

## Documentation Structure

| Section | Description |
|---------|-------------|
| **Getting Started** | Account creation, joining productions, app navigation |
| **Productions** | Creating/managing productions, people, characters, production structure |
| **Scripts** | Uploading scripts, page navigation, script variants |
| **Annotations** | Highlights, notes, cues, tags, and the layer system |
| **Blocking** | Blocking editor, character stickers, blocking thumbnails |
| **Collaboration** | Inviting team members, roles & permissions, sharing & exporting |
| **Account & Settings** | Profile settings, company management |

## Local Development

### Prerequisites

- Python 3.x

### Setup

```bash
python -m venv venv
source venv/bin/activate
pip install mkdocs-material
```

### Run locally

```bash
mkdocs serve
```

The site will be available at `http://127.0.0.1:8000`.

### Build

```bash
mkdocs build
```

Static output is generated in the `site/` directory.

## Deployment

The site deploys automatically to GitHub Pages on every push to `main` via GitHub Actions. The workflow:

1. Builds the static site with `mkdocs build`
2. Deploys to GitHub Pages at [help.scriptmagic.app](https://help.scriptmagic.app)

See [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) for the full configuration.

## Contributing

All documentation lives in the `docs/` directory as Markdown files. The site navigation is configured in [`mkdocs.yml`](mkdocs.yml).

To add or edit a page:

1. Create or modify a `.md` file in the appropriate `docs/` subdirectory
2. If adding a new page, add it to the `nav` section in `mkdocs.yml`
3. Push to `main` to trigger a deploy
