---
layout: default
title: "malcolm-and-marie Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# malcolm-and-marie sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Malcolm & Marie |
| Collection key | `malcolm-and-marie` |
| imdb_id | [tt12676326](https://www.imdb.com/title/tt12676326/) |
| wikipedia_url | [Malcolm & Marie](https://en.wikipedia.org/wiki/Malcolm_%26_Marie) |
| Sample dates | 2021-02-05-to-2021-04-15 |
| Sample days | 70 |
| BTIH count | 93 |
| Unique BTIH count | 68 |
| Downloaders total | 2,795,294 |
| Uploaders total | 487,705 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-02-05 to 2021-04-15 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Malcolm & Marie collection size histogram](figures/malcolm-and-marie-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/malcolm-and-marie-downloads-by-week-malcolm-and-marie-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![malcolm-and-marie downloads by day](figures/malcolm-and-marie-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/malcolm-and-marie-cumulative-aggregate.geojson.gz" data-map-title="Malcolm &amp; Marie — malcolm-and-marie" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Malcolm &amp; Marie (malcolm-and-marie) cumulative data map in new window" title="Opens interactive map for Malcolm &amp; Marie (malcolm-and-marie) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 15.98 | 28.42 | 21.54 | 19.38 | 1.43 | 8.23 |

### Network infrastructure

[![Malcolm & Marie cumulative map](figures/malcolm-and-marie-carto.png)](figures/malcolm-and-marie-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/malcolm-and-marie-data-ge-1080p.webp)](figures/malcolm-and-marie-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/malcolm-and-marie-data-lt-1080p.webp)](figures/malcolm-and-marie-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
