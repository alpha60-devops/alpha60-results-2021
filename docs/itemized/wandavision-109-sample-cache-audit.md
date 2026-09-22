---
layout: default
title: "wandavision-109 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# wandavision-109 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | WandaVision |
| Collection key | `wandavision-109` |
| imdb_id | [tt9140560](https://www.imdb.com/title/tt9140560/) |
| wikipedia_url | [WandaVision](https://en.wikipedia.org/wiki/WandaVision) |
| Sample dates | 2021-03-05-to-2021-09-02 |
| Sample days | 182 |
| BTIH count | 219 |
| Unique BTIH count | 193 |
| Downloaders total | 24,535,631 |
| Uploaders total | 3,898,491 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-03-05 to 2021-09-02 (182 days)
- Cache Day products: 180
- Sparse Day indices: 2
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index 158: `2021-08-09`
- missing Day index 159: `2021-08-10`

## 3. File sizes histogram *median[lowest, highest]*

![WandaVision collection size histogram](figures/wandavision-109-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/wandavision-109-downloads-by-week-wandavision-109-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![wandavision-109 downloads by day](figures/wandavision-109-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/wandavision-109-cumulative-aggregate.geojson.gz" data-map-title="WandaVision — wandavision-109" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open WandaVision (wandavision-109) cumulative data map in new window" title="Opens interactive map for WandaVision (wandavision-109) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.00 | 35.72 | 22.23 | 26.27 | 1.47 | 8.06 |

### Network infrastructure

[![WandaVision cumulative map](figures/wandavision-109-carto.png)](figures/wandavision-109-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/wandavision-109-data-ge-1080p.webp)](figures/wandavision-109-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/wandavision-109-data-lt-1080p.webp)](figures/wandavision-109-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
