---
layout: default
title: "outer-banks-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# outer-banks-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Outer Banks |
| Collection key | `outer-banks-02` |
| imdb_id | [tt10293938](https://www.imdb.com/title/tt10293938/) |
| wikipedia_url | [Outer Banks (TV series)](https://en.wikipedia.org/wiki/Outer_Banks_(TV_series)) |
| Sample dates | 2021-07-30-to-2021-10-07 |
| Sample days | 70 |
| BTIH count | 179 |
| Unique BTIH count | 174 |
| Downloaders total | 4,423,511 |
| Uploaders total | 270,969 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-07-30 to 2021-10-07 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Outer Banks collection size histogram](figures/outer-banks-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/outer-banks-02-downloads-by-week-outer-banks-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![outer-banks-02 downloads by day](figures/outer-banks-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.68 | 36.09 | 18.66 | 26.11 | 1.37 | 10.76 |

### Cumulative network infrastructure

[![Outer Banks cumulative map](figures/outer-banks-02-carto.png)](figures/outer-banks-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/outer-banks-02-data-ge-1080p.webp)](figures/outer-banks-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/outer-banks-02-data-lt-1080p.webp)](figures/outer-banks-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
