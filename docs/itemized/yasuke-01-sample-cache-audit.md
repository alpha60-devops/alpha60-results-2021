---
layout: default
title: "yasuke-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# yasuke-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Yasuke |
| Collection key | `yasuke-01` |
| imdb_id | [tt9310330](https://www.imdb.com/title/tt9310330/) |
| wikipedia_url | [Yasuke (TV series)](https://en.wikipedia.org/wiki/Yasuke_(TV_series)) |
| Sample dates | 2021-04-29-to-2021-07-07 |
| Sample days | 70 |
| BTIH count | 144 |
| Unique BTIH count | 128 |
| Downloaders total | 6,073,908 |
| Uploaders total | 523,296 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-04-29 to 2021-07-07 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Yasuke collection size histogram](figures/yasuke-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/yasuke-01-downloads-by-week-yasuke-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![yasuke-01 downloads by day](figures/yasuke-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.76 | 36.70 | 18.73 | 20.20 | 1.29 | 10.41 |

### Cumulative network infrastructure

[![Yasuke cumulative map](figures/yasuke-01-carto.png)](figures/yasuke-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/yasuke-01-data-ge-1080p.webp)](figures/yasuke-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/yasuke-01-data-lt-1080p.webp)](figures/yasuke-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
