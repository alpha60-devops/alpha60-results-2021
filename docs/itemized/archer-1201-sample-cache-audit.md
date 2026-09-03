---
layout: default
title: "archer-1201 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# archer-1201 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Archer |
| Collection key | `archer-1201` |
| imdb_id | [tt1486217](https://www.imdb.com/title/tt1486217/) |
| wikipedia_url | [Archer (2009 TV series)](https://en.wikipedia.org/wiki/Archer_(2009_TV_series)) |
| Sample dates | 2021-08-26-to-2021-11-03 |
| Sample days | 70 |
| BTIH count | 126 |
| Unique BTIH count | 109 |
| Downloaders total | 3,847,520 |
| Uploaders total | 340,359 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-08-26 to 2021-11-03 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Archer collection size histogram](figures/archer-1201-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/archer-1201-downloads-by-week-archer-1201-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![archer-1201 downloads by day](figures/archer-1201-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.89 | 36.21 | 17.71 | 28.35 | 2.42 | 9.40 |

### Cumulative network infrastructure

[![Archer cumulative map](figures/archer-1201-carto.png)](figures/archer-1201-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/archer-1201-data-ge-1080p.webp)](figures/archer-1201-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/archer-1201-data-lt-1080p.webp)](figures/archer-1201-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
