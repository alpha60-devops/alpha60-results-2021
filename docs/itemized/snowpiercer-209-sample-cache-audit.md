---
layout: default
title: "snowpiercer-209 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# snowpiercer-209 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Snowpiercer |
| Collection key | `snowpiercer-209` |
| imdb_id | [tt6156584](https://www.imdb.com/title/tt6156584/) |
| wikipedia_url | [Snowpiercer (TV series)](https://en.wikipedia.org/wiki/Snowpiercer_(TV_series)) |
| Sample dates | 2021-03-30-to-2021-06-07 |
| Sample days | 70 |
| BTIH count | 171 |
| Unique BTIH count | 154 |
| Downloaders total | 4,418,432 |
| Uploaders total | 386,509 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-03-30 to 2021-06-07 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Snowpiercer collection size histogram](figures/snowpiercer-209-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/snowpiercer-209-downloads-by-week-snowpiercer-209-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![snowpiercer-209 downloads by day](figures/snowpiercer-209-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/snowpiercer-209-cumulative-aggregate.geojson.gz" data-map-title="Snowpiercer — snowpiercer-209" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Snowpiercer (snowpiercer-209) cumulative data map in new window" title="Opens interactive map for Snowpiercer (snowpiercer-209) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.94 | 35.57 | 17.98 | 28.09 | 1.64 | 10.41 |

### Network infrastructure

[![Snowpiercer cumulative map](figures/snowpiercer-209-carto.png)](figures/snowpiercer-209-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/snowpiercer-209-data-ge-1080p.webp)](figures/snowpiercer-209-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/snowpiercer-209-data-lt-1080p.webp)](figures/snowpiercer-209-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
