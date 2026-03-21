# RichardGeorgeDavis.github.io

Personal landing page for Richard George Davis, published with GitHub Pages.

![Site cover](cover.png)

## Overview

This repository contains a lightweight static site with:

- a single hand-written [`index.html`](/Users/richard/Local Sites/Codex Workspace/repos/landing-pages/RichardGeorgeDavis.github.io/index.html) file
- inline CSS for layout, typography, color themes, and motion
- inline JavaScript for light/dark theme persistence via `localStorage`
- GitHub Pages deployment from the repository root

The page presents a concise portfolio and contact surface built around three areas:

- strategy architecture
- experience design
- execution and prototyping

## Project Structure

- [`index.html`](/Users/richard/Local Sites/Codex Workspace/repos/landing-pages/RichardGeorgeDavis.github.io/index.html): complete site markup, styling, and behavior
- [`cover.png`](/Users/richard/Local Sites/Codex Workspace/repos/landing-pages/RichardGeorgeDavis.github.io/cover.png): repository preview image
- [`_config.yml`](/Users/richard/Local Sites/Codex Workspace/repos/landing-pages/RichardGeorgeDavis.github.io/_config.yml): GitHub Pages config
- [`.nojekyll`](/Users/richard/Local Sites/Codex Workspace/repos/landing-pages/RichardGeorgeDavis.github.io/.nojekyll): disables Jekyll processing on GitHub Pages

## Local Preview

Because the site is plain HTML, you can preview it with any static file server.

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

You can also open [`index.html`](/Users/richard/Local Sites/Codex Workspace/repos/landing-pages/RichardGeorgeDavis.github.io/index.html) directly in a browser for quick checks, but using a local server is closer to production behavior.

## Editing

- update hero copy, services, work, and contact content in the HTML sections
- adjust colors, spacing, and responsive behavior in the inline `<style>` block
- update theme toggle behavior in the inline `<script>` blocks
- replace outbound links such as the `rgd.bio.link` hub URL when needed

## Deployment

Push changes to the repository branch configured for GitHub Pages and the site will republish automatically.

This repository includes [`.nojekyll`](/Users/richard/Local Sites/Codex Workspace/repos/landing-pages/RichardGeorgeDavis.github.io/.nojekyll), so the page is served as a static site rather than processed as a Jekyll project.
