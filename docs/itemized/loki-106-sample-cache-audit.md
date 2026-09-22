---
layout: default
title: "loki-106 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# loki-106 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Loki |
| Collection key | `loki-106` |
| imdb_id | [tt9140554](https://www.imdb.com/title/tt9140554/) |
| wikipedia_url | [Loki (TV series)](https://en.wikipedia.org/wiki/Loki_(TV_series)) |
| Sample dates | 2021-07-14-to-2021-11-09 |
| Sample days | 119 |
| BTIH count | 287 |
| Unique BTIH count | 265 |
| Downloaders total | 21,440,310 |
| Uploaders total | 3,944,168 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-07-14 to 2021-11-09 (119 days)
- Cache Day products: 119
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Loki collection size histogram](figures/loki-106-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/loki-106-downloads-by-week-loki-106-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![loki-106 downloads by day](figures/loki-106-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/loki-106-cumulative-aggregate.geojson.gz" data-map-title="Loki — loki-106" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Loki (loki-106) cumulative data map in new window" title="Opens interactive map for Loki (loki-106) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.18 | 29.20 | 24.07 | 30.35 | 1.55 | 7.11 |

### Network infrastructure

[![Loki cumulative map](figures/loki-106-carto.png)](figures/loki-106-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/loki-106-data-ge-1080p.webp)](figures/loki-106-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/loki-106-data-lt-1080p.webp)](figures/loki-106-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
