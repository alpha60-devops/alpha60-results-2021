---
layout: default
title: "one-piece-95x Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# one-piece-95x sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | One Piece 95x |
| Collection key | `one-piece-95x` |
| imdb_id | [tt0388629](https://www.imdb.com/title/tt0388629/) |
| wikipedia_url | [One Piece (1999 TV series)](https://en.wikipedia.org/wiki/One_Piece_(1999_TV_series)) |
| Sample dates | 2021-04-02-to-2021-10-07 |
| Sample days | 189 |
| BTIH count | 324 |
| Unique BTIH count | 303 |
| Downloaders total | 12,391,986 |
| Uploaders total | 411,073 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-04-02 to 2021-10-07 (189 days)
- Cache Day products: 189
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![One Piece 95x collection size histogram](figures/one-piece-95x-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/one-piece-95x-downloads-by-week-one-piece-95x-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![one-piece-95x downloads by day](figures/one-piece-95x-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/one-piece-95x-cumulative-aggregate.geojson.gz" data-map-title="One Piece 95x — one-piece-95x" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open One Piece 95x (one-piece-95x) cumulative data map in new window" title="Opens interactive map for One Piece 95x (one-piece-95x) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.56 | 37.79 | 20.86 | 24.29 | 1.39 | 11.32 |

### Network infrastructure

[![One Piece 95x cumulative map](figures/one-piece-95x-carto.png)](figures/one-piece-95x-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/one-piece-95x-data-ge-1080p.webp)](figures/one-piece-95x-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/one-piece-95x-data-lt-1080p.webp)](figures/one-piece-95x-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
