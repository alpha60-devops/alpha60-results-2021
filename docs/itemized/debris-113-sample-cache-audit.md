---
layout: default
title: "debris-113 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# debris-113 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Debris |
| Collection key | `debris-113` |
| imdb_id | [tt11640020](https://www.imdb.com/title/tt11640020/) |
| wikipedia_url | [Debris (TV series)](https://en.wikipedia.org/wiki/Debris_(TV_series)) |
| Sample dates | 2021-05-25-to-2021-08-02 |
| Sample days | 70 |
| BTIH count | 79 |
| Unique BTIH count | 70 |
| Downloaders total | 3,533,601 |
| Uploaders total | 217,586 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-05-25 to 2021-08-02 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Debris collection size histogram](figures/debris-113-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/debris-113-downloads-by-week-debris-113-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![debris-113 downloads by day](figures/debris-113-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/debris-113-cumulative-aggregate.geojson.gz" data-map-title="Debris — debris-113" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Debris (debris-113) cumulative data map in new window" title="Opens interactive map for Debris (debris-113) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.54 | 38.46 | 17.81 | 25.27 | 1.53 | 11.06 |

### Network infrastructure

[![Debris cumulative map](figures/debris-113-carto.png)](figures/debris-113-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/debris-113-data-ge-1080p.webp)](figures/debris-113-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/debris-113-data-lt-1080p.webp)](figures/debris-113-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
