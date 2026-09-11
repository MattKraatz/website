# Working on this website

This repository contains Matt Kraatz's personal website at `mattkraatz.com`.
Read [SPEC.md](SPEC.md) for the site's purpose, content direction, and design requirements.

## Project structure

- `index.html`: the complete single-page site, including metadata and copy.
- `css/site.css`: shared styles and responsive layouts.
- `img/`: images used by the site.
- `CNAME`: the custom domain for GitHub Pages.
- `LICENSE`: retained MIT license and original attribution.

The site is plain HTML and CSS with no build step, package installation, or JavaScript runtime dependency. Google Fonts supplies Space Grotesk and IBM Plex Mono, with local font fallbacks defined in CSS.

## Local preview

From the repository root, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000`. Stop the server with Ctrl+C.

## Editing guidelines

- Keep the site static and lightweight. Add dependencies or build tooling only when a concrete requirement justifies them.
- Maintain semantic HTML, heading order, descriptive image alt text, keyboard focus indicators, and responsive layouts.
- Keep business outcomes and engineering judgment central to the copy. Do not invent employment details, metrics, endorsements, or project links. Retain qualifications such as "estimated," "approximately," and "potential" when editing claims.
- Use the current homepage as the content baseline. Update `SPEC.md` when the intended product or design direction changes.
- Keep only assets referenced by the site or needed for an explicitly planned feature. Git history contains retired files.
- Preserve `CNAME` and license attribution. Publishing and domain configuration are separate from local file changes; do not describe them as verified without checking them.
- Maintain durable guidance here and product requirements in `SPEC.md`; avoid adding one-off task prompts or completed implementation logs.

## Validation

There is no automated test suite or build command. Match validation to the change:

- Run `git diff --check` and confirm local image and stylesheet references resolve.
- For presentation or markup changes, preview desktop and narrow mobile layouts; check for overflow, readable text, image sizing, and keyboard navigation.
- For content changes, review page title, description, headings, factual claims, and outbound links.
- Report what was checked and any validation that could not be completed.
