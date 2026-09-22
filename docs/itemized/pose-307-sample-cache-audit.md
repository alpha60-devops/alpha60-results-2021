---
layout: default
title: "pose-307 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# pose-307 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Pose |
| Collection key | `pose-307` |
| imdb_id | [tt7562112](https://www.imdb.com/title/tt7562112/) |
| wikipedia_url | [Pose (TV series)](https://en.wikipedia.org/wiki/Pose_(TV_series)) |
| Sample dates | 2021-06-07-to-2021-08-15 |
| Sample days | 70 |
| BTIH count | 75 |
| Unique BTIH count | 64 |
| Downloaders total | 1,824,833 |
| Uploaders total | 172,013 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-06-07 to 2021-08-15 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Pose collection size histogram](figures/pose-307-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/pose-307-downloads-by-week-pose-307-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![pose-307 downloads by day](figures/pose-307-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/pose-307-cumulative-aggregate.geojson.gz" data-map-title="Pose — pose-307" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Pose (pose-307) cumulative data map in new window" title="Opens interactive map for Pose (pose-307) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.10 | 41.48 | 17.32 | 22.37 | 1.50 | 9.88 |

### Network infrastructure

[![Pose cumulative map](figures/pose-307-carto.png)](figures/pose-307-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/pose-307-data-ge-1080p.webp)](figures/pose-307-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/pose-307-data-lt-1080p.webp)](figures/pose-307-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
