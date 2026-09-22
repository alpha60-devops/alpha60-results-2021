---
layout: default
title: "expanse-601 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# expanse-601 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Expanse |
| Collection key | `expanse-601` |
| imdb_id | [tt3230854](https://www.imdb.com/title/tt3230854/) |
| wikipedia_url | [The Expanse (TV series)](https://en.wikipedia.org/wiki/The_Expanse_(TV_series)) |
| Sample dates | 2021-12-10-to-2022-02-24 |
| Sample days | 77 |
| BTIH count | 177 |
| Unique BTIH count | 126 |
| Downloaders total | 2,704,344 |
| Uploaders total | 724,415 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-12-10 to 2022-02-24 (77 days)
- Cache Day products: 76
- Sparse Day indices: 1
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index 52: `2022-01-30`

## 3. File sizes histogram *median[lowest, highest]*

![The Expanse collection size histogram](figures/expanse-601-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/expanse-601-downloads-by-week-expanse-601-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![expanse-601 downloads by day](figures/expanse-601-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/expanse-601-cumulative-aggregate.geojson.gz" data-map-title="The Expanse — expanse-601" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Expanse (expanse-601) cumulative data map in new window" title="Opens interactive map for The Expanse (expanse-601) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.23 | 21.14 | 15.99 | 51.99 | 3.14 | 1.09 |

### Network infrastructure

[![The Expanse cumulative map](figures/expanse-601-carto.png)](figures/expanse-601-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/expanse-601-data-ge-1080p.webp)](figures/expanse-601-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/expanse-601-data-lt-1080p.webp)](figures/expanse-601-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
