---
layout: default
title: "doors Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# doors sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Doors |
| Collection key | `doors` |
| imdb_id | [tt12483708](https://www.imdb.com/title/tt12483708/) |
| wikipedia_url | [Doors (film)](https://en.wikipedia.org/wiki/Doors_(film)) |
| Sample dates | 2021-03-23-to-2021-05-31 |
| Sample days | 70 |
| BTIH count | 56 |
| Unique BTIH count | 44 |
| Downloaders total | 1,865,330 |
| Uploaders total | 278,435 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-03-23 to 2021-05-31 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Doors collection size histogram](figures/doors-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/doors-downloads-by-week-doors-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![doors downloads by day](figures/doors-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/doors-cumulative-aggregate.geojson.gz" data-map-title="Doors — doors" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Doors (doors) cumulative data map in new window" title="Opens interactive map for Doors (doors) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.07 | 29.39 | 19.08 | 27.07 | 1.99 | 7.56 |

### Network infrastructure

[![Doors cumulative map](figures/doors-carto.png)](figures/doors-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/doors-data-ge-1080p.webp)](figures/doors-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/doors-data-lt-1080p.webp)](figures/doors-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
