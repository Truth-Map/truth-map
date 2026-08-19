# Path A Site Build Notes

Internal-facing summary of the interactive site build (for contributors and operators).

## Decisions locked

- **Stack:** Path A — Markdown source of truth → static/hybrid public site + client-side map/graph
- **Anonymity:** Operator priority is not to dox themselves; org accounts preferred; no third-party trackers on the preview
- **Hosting:** Third-party static preferred; always-on backend not required for v1
- **Schema:** SCHEMA-v1 frozen (universal fields + type extensions + map/edge shapes)

## Current artifacts

- Research process: private OS + local KB (`web-vision/SITE-BUILD-PROCESS.md`)
- Public preview: [`preview/site-scaffold.html`](https://github.com/Truth-Map/truth-map/blob/main/preview/site-scaffold.html)
- Main published site (MkDocs): [truth-map.github.io/truth-map](https://truth-map.github.io/truth-map/)

## How to view the interactive preview

[htmlpreview link](https://htmlpreview.github.io/?https://github.com/Truth-Map/truth-map/blob/main/preview/site-scaffold.html)

## Next build bites

1. Expand parsers (Person / Org) so more cards generate automatically  
2. Improve evidence extraction quality  
3. Real Astro or Next static project when ready  
4. Point a clean URL at the interactive surface (Pages subpath or separate host)  
