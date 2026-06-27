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

All design candidates are kept under `/preview`, named `v<generation><variant>` so the decision path is visible: **gen 1** explored `community` vs `minimal` (community was chosen and evolved into **gen 2**, offered as `blue` vs `plum`).

| Preview | What it is | Link |
|---------|------------|------|
| **v1community** | Gen 1 — full community landing, features, testimonials, sponsors *(chosen)* | https://saeedtaghavi.github.io/labmatters-landing/preview/v1community |
| **v1minimal** | Gen 1 — minimal landing, the essentials only | https://saeedtaghavi.github.io/labmatters-landing/preview/v1minimal |
| **v2blue** | Gen 2 — current design, navy/blue theme | https://saeedtaghavi.github.io/labmatters-landing/preview/v2blue |
| **v2plum** | Gen 2 — current design, plum/soft-pink theme (brand colours) | https://saeedtaghavi.github.io/labmatters-landing/preview/v2plum |

> Tip: add a trailing slash if a link 404s — e.g. `…/preview/v2blue/`.

## Repository structure

```
labmatters-landing/
├── index.html        # live site (the chosen design)
├── assets/           # logos + illustrations for the live site
├── preview/
│   ├── v1community/  # gen 1 — full community landing (chosen)
│   ├── v1minimal/    # gen 1 — minimal landing
│   ├── v2blue/       # gen 2 — navy/blue theme
│   └── v2plum/       # gen 2 — plum/soft-pink theme
└── README.md
```

Each landing is self-contained: keep its `index.html` and `assets/` folder together, since pages reference images by relative path (`assets/…`).


