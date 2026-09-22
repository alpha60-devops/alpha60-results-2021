---
layout: default
title: "invincible-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# invincible-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Invincible |
| Collection key | `invincible-101` |
| imdb_id | [tt6741278](https://www.imdb.com/title/tt6741278/) |
| wikipedia_url | [Invincible (TV series)](https://en.wikipedia.org/wiki/Invincible_(TV_series)) |
| Sample dates | 2021-03-26-to-2021-06-03 |
| Sample days | 70 |
| BTIH count | 104 |
| Unique BTIH count | 97 |
| Downloaders total | 3,690,329 |
| Uploaders total | 718,767 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-03-26 to 2021-06-03 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Invincible collection size histogram](figures/invincible-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/invincible-101-downloads-by-week-invincible-101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![invincible-101 downloads by day](figures/invincible-101-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/invincible-101-cumulative-aggregate.geojson.gz" data-map-title="Invincible — invincible-101" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Invincible (invincible-101) cumulative data map in new window" title="Opens interactive map for Invincible (invincible-101) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.58 | 37.19 | 19.71 | 20.77 | 2.49 | 7.17 |

### Network infrastructure

[![Invincible cumulative map](figures/invincible-101-carto.png)](figures/invincible-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/invincible-101-data-ge-1080p.webp)](figures/invincible-101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/invincible-101-data-lt-1080p.webp)](figures/invincible-101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
