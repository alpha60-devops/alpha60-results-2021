---
layout: default
title: "matrix-resurrections Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# matrix-resurrections sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Matrix Resurrections (2021) |
| Collection key | `matrix-resurrections` |
| imdb_id | [tt10838180](https://www.imdb.com/title/tt10838180/) |
| wikipedia_url | [The Matrix Resurrections](https://en.wikipedia.org/wiki/The_Matrix_Resurrections) |
| Sample dates | 2021-12-22-to-2022-06-21 |
| Sample days | 182 |
| BTIH count | 521 |
| Unique BTIH count | 430 |
| Downloaders total | 40,096,521 |
| Uploaders total | 13,749,939 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-12-22 to 2022-06-21 (182 days)
- Cache Day products: 182
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![The Matrix Resurrections (2021) collection size histogram](figures/matrix-resurrections-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/matrix-resurrections-downloads-by-week-matrix-resurrections-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![matrix-resurrections downloads by day](figures/matrix-resurrections-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 8.49 | 17.94 | 27.57 | 36.61 | 2.26 | 0.72 |

### Cumulative network infrastructure

[![The Matrix Resurrections (2021) cumulative map](figures/matrix-resurrections-carto.png)](figures/matrix-resurrections-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/matrix-resurrections-data-ge-1080p.webp)](figures/matrix-resurrections-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/matrix-resurrections-data-lt-1080p.webp)](figures/matrix-resurrections-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
