---
layout: default
title: "no-time-to-die Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# no-time-to-die sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | No Time To Die |
| Collection key | `no-time-to-die` |
| imdb_id | [tt2382320](https://www.imdb.com/title/tt2382320/) |
| wikipedia_url | [No Time to Die](https://en.wikipedia.org/wiki/No_Time_to_Die) |
| Sample dates | 2021-11-09-to-2022-02-28 |
| Sample days | 112 |
| BTIH count | 321 |
| Unique BTIH count | 265 |
| Downloaders total | 27,254,194 |
| Uploaders total | 9,377,895 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-11-09 to 2022-02-28 (112 days)
- Cache Day products: 112
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![No Time To Die collection size histogram](figures/no-time-to-die-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/no-time-to-die-downloads-by-week-no-time-to-die-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![no-time-to-die downloads by day](figures/no-time-to-die-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 7.29 | 15.34 | 31.64 | 34.36 | 2.17 | 1.04 |

### Cumulative network infrastructure

[![No Time To Die cumulative map](figures/no-time-to-die-carto.png)](figures/no-time-to-die-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/no-time-to-die-data-ge-1080p.webp)](figures/no-time-to-die-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/no-time-to-die-data-lt-1080p.webp)](figures/no-time-to-die-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
