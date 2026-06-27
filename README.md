<p align="center">
  <img src="assets/logo-wordmark.png" alt="LabMatters" width="360">
</p>

<h1 align="center">LabMatters — Landing Pages</h1>

<p align="center">
  Landing pages for <strong>LabMatters</strong>, the community &amp; knowledge hub for experimental research labs (built on Discourse), and <strong>PRISM</strong>, our document-digitalisation solution.
</p>

## Live site

The selected design is served from the repository root:

**https://saeedtaghavi.github.io/labmatters-landing/**

## Previews

All design candidates are kept under `/preview` so they stay browsable side by side.

| Preview | What it is | Link |
|---------|------------|------|
| **blue** | Current design — navy/blue theme | https://saeedtaghavi.github.io/labmatters-landing/preview/blue |
| **plum** | Current design — plum/soft-pink theme (brand colours) | https://saeedtaghavi.github.io/labmatters-landing/preview/plum |
| **community** | Full community landing (features, testimonials, sponsors) | https://saeedtaghavi.github.io/labmatters-landing/preview/community |
| **minimal** | Minimal landing — the essentials only | https://saeedtaghavi.github.io/labmatters-landing/preview/minimal |

> Tip: add a trailing slash if a link 404s — e.g. `…/preview/blue/`.

## Repository structure

```
labmatters-landing/
├── index.html        # live site (the chosen design)
├── assets/           # logos + illustrations for the live site
├── preview/
│   ├── blue/         # current design — navy/blue theme
│   ├── plum/         # current design — plum/soft-pink theme
│   ├── community/    # full community landing (was v1)
│   └── minimal/      # minimal landing (was v2)
└── README.md
```

Each landing is self-contained: keep its `index.html` and `assets/` folder together, since pages reference images by relative path (`assets/…`).


