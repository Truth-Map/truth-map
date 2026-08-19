# Truth Map — Path A Interactive Site (Phase 3)

**Status:** Skeleton + data package live  
**Schema:** SCHEMA-v1 (frozen)

## Files

| Path | Role |
|------|------|
| `index.html` | App shell |
| `app.js` | Renders cards from JSON + filters |
| `styles.css` | Presentation |
| `data/cards.json` | **12 SCHEMA-v1 cards** (origins cluster) |
| `data/map-nodes.json` | Facility coordinates |

## How to view

### Working now (no setup)

Embedded origins preview:

**[Open preview](https://htmlpreview.github.io/?https://github.com/Truth-Map/truth-map/blob/main/preview/site-scaffold.html)**

### Phase 3 data-driven app

Needs HTTP (browser `fetch` for `data/cards.json`). Try:

**[raw.githack interactive](https://raw.githack.com/Truth-Map/truth-map/main/interactive/index.html)**

Or enable GitHub Pages from repo root later so this folder is first-class.

Main MkDocs site: [truth-map.github.io/truth-map](https://truth-map.github.io/truth-map/)

## Phase status

| Phase | Status |
|-------|--------|
| 0 Decisions (Path A + anonymity) | Locked |
| 1 SCHEMA-v1 | Frozen |
| 2 Ingest + origins sample | Residual-clean |
| **3 Data-driven static site** | **Skeleton + data live** |

## Anonymity

No third-party trackers. Operator identity not in public packages.
