---
layout: default
title: "for-all-mankind-210 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# for-all-mankind-210 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | For All Mankind |
| Collection key | `for-all-mankind-210` |
| imdb_id | [tt7772588](https://www.imdb.com/title/tt7772588/) |
| wikipedia_url | [For All Mankind (TV series)](https://en.wikipedia.org/wiki/For_All_Mankind_(TV_series)) |
| Sample dates | 2021-04-23-to-2021-07-08 |
| Sample days | 77 |
| BTIH count | 103 |
| Unique BTIH count | 81 |
| Downloaders total | 2,947,122 |
| Uploaders total | 210,504 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-04-23 to 2021-07-08 (77 days)
- Cache Day products: 77
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![For All Mankind collection size histogram](figures/for-all-mankind-210-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/for-all-mankind-210-downloads-by-week-for-all-mankind-210-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![for-all-mankind-210 downloads by day](figures/for-all-mankind-210-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/for-all-mankind-210-cumulative-aggregate.geojson.gz" data-map-title="For All Mankind — for-all-mankind-210" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open For All Mankind (for-all-mankind-210) cumulative data map in new window" title="Opens interactive map for For All Mankind (for-all-mankind-210) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.25 | 39.59 | 17.84 | 24.97 | 1.77 | 10.47 |

### Network infrastructure

[![For All Mankind cumulative map](figures/for-all-mankind-210-carto.png)](figures/for-all-mankind-210-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/for-all-mankind-210-data-ge-1080p.webp)](figures/for-all-mankind-210-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/for-all-mankind-210-data-lt-1080p.webp)](figures/for-all-mankind-210-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
