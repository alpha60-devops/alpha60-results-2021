---
layout: default
title: "money-heist-05.1 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# money-heist-05.1 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | La Casa De Papel aka Money Heist |
| Collection key | `money-heist-05.1` |
| imdb_id | [tt6468322](https://www.imdb.com/title/tt6468322/) |
| wikipedia_url | [Money Heist](https://en.wikipedia.org/wiki/Money_Heist) |
| Sample dates | 2021-09-03-to-2021-12-16 |
| Sample days | 105 |
| BTIH count | 257 |
| Unique BTIH count | 242 |
| Downloaders total | 13,804,943 |
| Uploaders total | 3,853,124 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-10T15:44:12Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/money-heist-05.1.xz`
- Hour directories: 2511
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![La Casa De Papel aka Money Heist collection size histogram](figures/money-heist-05.1-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/money-heist-05-1-downloads-by-week-money-heist-05.1-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![money-heist-05.1 downloads by day](figures/money-heist-05-1-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2021/refs/heads/main/data/geojson.cumulative/money-heist-05.1-cumulative-aggregate.geojson.gz" data-map-title="La Casa De Papel aka Money Heist — money-heist-05.1" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open La Casa De Papel aka Money Heist (money-heist-05.1) cumulative data map in new window" title="Opens interactive map for La Casa De Papel aka Money Heist (money-heist-05.1) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 11.62 | 21.04 | 31.32 | 27.03 | 0.75 | 4.72 |

### Network infrastructure

[![La Casa De Papel aka Money Heist cumulative map](figures/money-heist-05.1-carto.png)](figures/money-heist-05.1-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/money-heist-05.1-data-ge-1080p.webp)](figures/money-heist-05.1-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/money-heist-05.1-data-lt-1080p.webp)](figures/money-heist-05.1-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
