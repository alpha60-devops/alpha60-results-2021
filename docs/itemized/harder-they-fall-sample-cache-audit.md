---
layout: default
title: "harder-they-fall Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# harder-they-fall sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Harder They Fall |
| Collection key | `harder-they-fall` |
| imdb_id | [tt10696784](https://www.imdb.com/title/tt10696784/) |
| wikipedia_url | [The Harder They Fall (2021 film)](https://en.wikipedia.org/wiki/The_Harder_They_Fall_(2021_film)) |
| Sample dates | 2021-11-03-to-2022-01-11 |
| Sample days | 70 |
| BTIH count | 120 |
| Unique BTIH count | 90 |
| Downloaders total | 3,484,476 |
| Uploaders total | 1,241,669 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-11-03 to 2022-01-11 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![The Harder They Fall collection size histogram](figures/harder-they-fall-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/harder-they-fall-downloads-by-week-harder-they-fall-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![harder-they-fall downloads by day](figures/harder-they-fall-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/harder-they-fall-cumulative-aggregate.geojson.gz" data-map-title="The Harder They Fall — harder-they-fall" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Harder They Fall (harder-they-fall) cumulative data map in new window" title="Opens interactive map for The Harder They Fall (harder-they-fall) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 19.11 | 17.15 | 20.87 | 32.06 | 2.54 | 0.66 |

### Network infrastructure

[![The Harder They Fall cumulative map](figures/harder-they-fall-carto.png)](figures/harder-they-fall-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/harder-they-fall-data-ge-1080p.webp)](figures/harder-they-fall-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/harder-they-fall-data-lt-1080p.webp)](figures/harder-they-fall-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
