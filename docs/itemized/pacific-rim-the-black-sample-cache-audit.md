---
layout: default
title: "pacific-rim-the-black Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# pacific-rim-the-black sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Pacific Rim The Black |
| Collection key | `pacific-rim-the-black` |
| imdb_id | [tt9288848](https://www.imdb.com/title/tt9288848/) |
| wikipedia_url | [Pacific Rim: The Black](https://en.wikipedia.org/wiki/Pacific_Rim:_The_Black) |
| Sample dates | 2021-03-04-to-2021-05-12 |
| Sample days | 70 |
| BTIH count | 91 |
| Unique BTIH count | 84 |
| Downloaders total | 1,939,339 |
| Uploaders total | 175,983 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-03-04 to 2021-05-12 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Pacific Rim The Black collection size histogram](figures/pacific-rim-the-black-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/pacific-rim-the-black-downloads-by-week-pacific-rim-the-black-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![pacific-rim-the-black downloads by day](figures/pacific-rim-the-black-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/pacific-rim-the-black-cumulative-aggregate.geojson.gz" data-map-title="Pacific Rim The Black — pacific-rim-the-black" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Pacific Rim The Black (pacific-rim-the-black) cumulative data map in new window" title="Opens interactive map for Pacific Rim The Black (pacific-rim-the-black) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.09 | 36.96 | 21.20 | 21.53 | 1.56 | 11.17 |

### Network infrastructure

[![Pacific Rim The Black cumulative map](figures/pacific-rim-the-black-carto.png)](figures/pacific-rim-the-black-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/pacific-rim-the-black-data-ge-1080p.webp)](figures/pacific-rim-the-black-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/pacific-rim-the-black-data-lt-1080p.webp)](figures/pacific-rim-the-black-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
