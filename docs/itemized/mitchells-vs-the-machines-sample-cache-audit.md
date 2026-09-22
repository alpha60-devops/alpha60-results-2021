---
layout: default
title: "mitchells-vs-the-machines Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# mitchells-vs-the-machines sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Mitchells vs The Machines |
| Collection key | `mitchells-vs-the-machines` |
| imdb_id | [tt7979580](https://www.imdb.com/title/tt7979580/) |
| wikipedia_url | [The Mitchells vs. the Machines](https://en.wikipedia.org/wiki/The_Mitchells_vs._the_Machines) |
| Sample dates | 2021-05-01-to-2021-07-09 |
| Sample days | 70 |
| BTIH count | 118 |
| Unique BTIH count | 83 |
| Downloaders total | 11,036,594 |
| Uploaders total | 2,777,975 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-05-01 to 2021-07-09 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![The Mitchells vs The Machines collection size histogram](figures/mitchells-vs-the-machines-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/mitchells-vs-the-machines-downloads-by-week-mitchells-vs-the-machines-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![mitchells-vs-the-machines downloads by day](figures/mitchells-vs-the-machines-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/mitchells-vs-the-machines-cumulative-aggregate.geojson.gz" data-map-title="The Mitchells vs The Machines — mitchells-vs-the-machines" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Mitchells vs The Machines (mitchells-vs-the-machines) cumulative data map in new window" title="Opens interactive map for The Mitchells vs The Machines (mitchells-vs-the-machines) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.44 | 23.78 | 25.11 | 28.94 | 1.64 | 6.07 |

### Network infrastructure

[![The Mitchells vs The Machines cumulative map](figures/mitchells-vs-the-machines-carto.png)](figures/mitchells-vs-the-machines-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/mitchells-vs-the-machines-data-ge-1080p.webp)](figures/mitchells-vs-the-machines-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/mitchells-vs-the-machines-data-lt-1080p.webp)](figures/mitchells-vs-the-machines-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
