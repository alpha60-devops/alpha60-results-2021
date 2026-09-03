---
layout: default
title: "loki-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# loki-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Loki |
| Collection key | `loki-101` |
| imdb_id | [tt9140554](https://www.imdb.com/title/tt9140554/) |
| wikipedia_url | [Loki (TV series)](https://en.wikipedia.org/wiki/Loki_(TV_series)) |
| Sample dates | 2021-06-09-to-2021-08-17 |
| Sample days | 70 |
| BTIH count | 259 |
| Unique BTIH count | 217 |
| Downloaders total | 19,517,789 |
| Uploaders total | 3,629,373 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-06-09 to 2021-08-17 (70 days)
- Cache Day products: 68
- Sparse Day indices: 2
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index 52: `2021-07-30`
- missing Day index 53: `2021-07-31`

## 3. Media objects file size histogram

![Loki collection size histogram](figures/loki-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/loki-101-downloads-by-week-loki-101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![loki-101 downloads by day](figures/loki-101-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.17 | 32.95 | 26.34 | 22.35 | 1.75 | 6.86 |

### Cumulative network infrastructure

[![Loki cumulative map](figures/loki-101-carto.png)](figures/loki-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/loki-101-data-ge-1080p.webp)](figures/loki-101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/loki-101-data-lt-1080p.webp)](figures/loki-101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
