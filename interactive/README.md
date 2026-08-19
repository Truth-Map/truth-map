# Truth Map — Path A Interactive Site (Phase 3)

**Status:** Skeleton opened 2026-08-19  
**Schema:** SCHEMA-v1 (frozen)

## What this is

The Phase 3 static site that **loads schema-shaped JSON** instead of hand-maintained HTML cards.

| Layer | Location |
|-------|----------|
| Working browser preview (today) | [`preview/site-scaffold.html`](../preview/site-scaffold.html) — open via [htmlpreview](https://htmlpreview.github.io/?https://github.com/Truth-Map/truth-map/blob/main/preview/site-scaffold.html) |
| Phase 3 source (data-driven) | this `interactive/` folder |
| Main MkDocs site | [truth-map.github.io/truth-map](https://truth-map.github.io/truth-map/) |

## Files

- `index.html` — app shell
- `app.js` — render + filter logic (fetch `data/cards.json` when served over HTTP)
- `styles.css` — presentation
- `data/cards.json` — public card package (SCHEMA-v1)
- `data/map-nodes.json` — facility coordinates

## Phase status

| Phase | Status |
|-------|--------|
| 0 Decisions (Path A + anonymity) | Locked |
| 1 SCHEMA-v1 | Frozen |
| 2 Ingest + origins sample cluster | Residual-clean |
| **3 Data-driven static site** | **Opened** |

## Anonymity

No third-party trackers. Operator identity not in public packages.
