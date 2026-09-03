---
layout: default
title: "lupin-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# lupin-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Lupin |
| Collection key | `lupin-02` |
| imdb_id | [tt2531336](https://www.imdb.com/title/tt2531336/) |
| wikipedia_url | [Lupin (French TV series)](https://en.wikipedia.org/wiki/Lupin_(French_TV_series)) |
| Sample dates | 2021-06-11-to-2021-09-23 |
| Sample days | 105 |
| BTIH count | 205 |
| Unique BTIH count | 192 |
| Downloaders total | 12,051,517 |
| Uploaders total | 1,423,078 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-06-11 to 2021-09-23 (105 days)
- Cache Day products: 105
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Lupin collection size histogram](figures/lupin-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/lupin-02-downloads-by-week-lupin-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![lupin-02 downloads by day](figures/lupin-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.68 | 34.75 | 18.25 | 27.50 | 1.25 | 10.19 |

### Cumulative network infrastructure

[![Lupin cumulative map](figures/lupin-02-carto.png)](figures/lupin-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/lupin-02-data-ge-1080p.webp)](figures/lupin-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/lupin-02-data-lt-1080p.webp)](figures/lupin-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
