---
layout: default
title: "black-monday-310 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# black-monday-310 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Black Monday |
| Collection key | `black-monday-310` |
| imdb_id | [tt7406334](https://www.imdb.com/title/tt7406334/) |
| wikipedia_url | [Black Monday (TV series)](https://en.wikipedia.org/wiki/Black_Monday_(TV_series)) |
| Sample dates | 2021-08-01-to-2021-08-03 |
| Sample days | 3 |
| BTIH count | 21 |
| Unique BTIH count | 21 |
| Downloaders total | 19,481 |
| Uploaders total | 3,370 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-10T15:44:03Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/black-monday-310.xz`
- Hour directories: 31
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Black Monday collection size histogram](figures/black-monday-310-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/black-monday-310-downloads-by-week-black-monday-310-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![black-monday-310 downloads by day](figures/black-monday-310-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/black-monday-310-cumulative-aggregate.geojson.gz" data-map-title="Black Monday — black-monday-310" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Black Monday (black-monday-310) cumulative data map in new window" title="Opens interactive map for Black Monday (black-monday-310) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.77 | 27.72 | 10.66 | 25.45 | 2.54 | 4.32 |

### Network infrastructure

[![Black Monday cumulative map](figures/black-monday-310-carto.png)](figures/black-monday-310-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/black-monday-310-data-ge-1080p.webp)](figures/black-monday-310-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/black-monday-310-data-lt-1080p.webp)](figures/black-monday-310-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
