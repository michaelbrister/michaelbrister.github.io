# michaelbrister.github.io

Personal site built with Hugo using the `hugo-resume` theme.

## Local development

```bash
hugo server -D
```

Open `http://localhost:1313`.

## Build check

```bash
hugo -D --cleanDestinationDir
```

## Content conventions

- Profile summary: `content/_index.md`
- Experience timeline (canonical): `data/experience.json`
- Skills (canonical): `data/skills.json`
- Contact page: `content/contact.md`
- Detailed resume page: `content/resume.md`

## Theme + customization

- Active theme: `themes/hugo-resume`
- Site config: `config.toml`
- Local nav override: `layouts/partials/nav.html`
- Local style overrides: `static/css/resume-override.css`

## Notes

- Keep `hugo-resume` as the only theme submodule.
- Prefer editing `data/*.json` for homepage sections to avoid duplicate content drift.
