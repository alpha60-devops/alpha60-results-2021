---
layout: default
title: "cowboy-bebop-2021-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# cowboy-bebop-2021-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Cowboy Bebop 2021 |
| Collection key | `cowboy-bebop-2021-01` |
| imdb_id | [tt1267295](https://www.imdb.com/title/tt1267295/) |
| wikipedia_url | [Cowboy Bebop (2021 TV series)](https://en.wikipedia.org/wiki/Cowboy_Bebop_(2021_TV_series)) |
| Sample dates | 2021-11-19-to-2022-01-27 |
| Sample days | 70 |
| BTIH count | 329 |
| Unique BTIH count | 254 |
| Downloaders total | 3,940,870 |
| Uploaders total | 1,146,327 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-11-19 to 2022-01-27 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Cowboy Bebop 2021 collection size histogram](figures/cowboy-bebop-2021-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/cowboy-bebop-2021-01-downloads-by-week-cowboy-bebop-2021-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![cowboy-bebop-2021-01 downloads by day](figures/cowboy-bebop-2021-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.47 | 18.74 | 16.84 | 53.54 | 1.78 | 0.96 |

### Cumulative network infrastructure

[![Cowboy Bebop 2021 cumulative map](figures/cowboy-bebop-2021-01-carto.png)](figures/cowboy-bebop-2021-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/cowboy-bebop-2021-01-data-ge-1080p.webp)](figures/cowboy-bebop-2021-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/cowboy-bebop-2021-01-data-lt-1080p.webp)](figures/cowboy-bebop-2021-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
