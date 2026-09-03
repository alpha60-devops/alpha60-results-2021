---
layout: default
title: "no-sudden-move Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# no-sudden-move sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | No Sudden Move |
| Collection key | `no-sudden-move` |
| imdb_id | [tt11525644](https://www.imdb.com/title/tt11525644/) |
| wikipedia_url | [No Sudden Move](https://en.wikipedia.org/wiki/No_Sudden_Move) |
| Sample dates | 2021-07-01-to-2021-09-08 |
| Sample days | 70 |
| BTIH count | 103 |
| Unique BTIH count | 87 |
| Downloaders total | 5,222,041 |
| Uploaders total | 965,073 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-07-01 to 2021-09-08 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![No Sudden Move collection size histogram](figures/no-sudden-move-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/no-sudden-move-downloads-by-week-no-sudden-move-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![no-sudden-move downloads by day](figures/no-sudden-move-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.54 | 28.79 | 19.67 | 29.42 | 2.33 | 6.47 |

### Cumulative network infrastructure

[![No Sudden Move cumulative map](figures/no-sudden-move-carto.png)](figures/no-sudden-move-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/no-sudden-move-data-ge-1080p.webp)](figures/no-sudden-move-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/no-sudden-move-data-lt-1080p.webp)](figures/no-sudden-move-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
