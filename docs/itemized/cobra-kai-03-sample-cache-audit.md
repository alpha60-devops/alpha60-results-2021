---
layout: default
title: "cobra-kai-03 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# cobra-kai-03 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Cobra Kai |
| Collection key | `cobra-kai-03` |
| imdb_id | [tt7221388](https://www.imdb.com/title/tt7221388/) |
| wikipedia_url | [Cobra Kai](https://en.wikipedia.org/wiki/Cobra_Kai) |
| Sample dates | 2021-01-01-to-2021-03-11 |
| Sample days | 70 |
| BTIH count | 156 |
| Unique BTIH count | 136 |
| Downloaders total | 2,145,367 |
| Uploaders total | 906,387 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-01-01 to 2021-03-11 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Cobra Kai collection size histogram](figures/cobra-kai-03-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/cobra-kai-03-downloads-by-week-cobra-kai-03-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![cobra-kai-03 downloads by day](figures/cobra-kai-03-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/cobra-kai-03-cumulative-aggregate.geojson.gz" data-map-title="Cobra Kai — cobra-kai-03" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Cobra Kai (cobra-kai-03) cumulative data map in new window" title="Opens interactive map for Cobra Kai (cobra-kai-03) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.22 | 28.21 | 18.69 | 28.60 | 3.94 | 0.57 |

### Network infrastructure

[![Cobra Kai cumulative map](figures/cobra-kai-03-carto.png)](figures/cobra-kai-03-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/cobra-kai-03-data-ge-1080p.webp)](figures/cobra-kai-03-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/cobra-kai-03-data-lt-1080p.webp)](figures/cobra-kai-03-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
