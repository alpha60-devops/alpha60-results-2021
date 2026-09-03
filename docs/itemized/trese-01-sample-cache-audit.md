---
layout: default
title: "trese-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# trese-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Trese |
| Collection key | `trese-01` |
| imdb_id | [tt9310336](https://www.imdb.com/title/tt9310336/) |
| wikipedia_url | [Trese (TV series)](https://en.wikipedia.org/wiki/Trese_(TV_series)) |
| Sample dates | 2021-06-11-to-2021-08-19 |
| Sample days | 70 |
| BTIH count | 131 |
| Unique BTIH count | 122 |
| Downloaders total | 4,465,821 |
| Uploaders total | 217,645 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-06-11 to 2021-08-19 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Trese collection size histogram](figures/trese-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/trese-01-downloads-by-week-trese-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![trese-01 downloads by day](figures/trese-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.45 | 38.76 | 20.63 | 22.71 | 1.29 | 11.63 |

### Cumulative network infrastructure

[![Trese cumulative map](figures/trese-01-carto.png)](figures/trese-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/trese-01-data-ge-1080p.webp)](figures/trese-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/trese-01-data-lt-1080p.webp)](figures/trese-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
