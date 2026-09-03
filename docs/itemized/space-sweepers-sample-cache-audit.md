---
layout: default
title: "space-sweepers Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# space-sweepers sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Space Sweepers |
| Collection key | `space-sweepers` |
| imdb_id | [tt12838766](https://www.imdb.com/title/tt12838766/) |
| wikipedia_url | [Space Sweepers](https://en.wikipedia.org/wiki/Space_Sweepers) |
| Sample dates | 2021-02-05-to-2021-04-15 |
| Sample days | 70 |
| BTIH count | 169 |
| Unique BTIH count | 126 |
| Downloaders total | 5,447,958 |
| Uploaders total | 2,381,715 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-02-05 to 2021-04-15 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Space Sweepers collection size histogram](figures/space-sweepers-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/space-sweepers-downloads-by-week-space-sweepers-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![space-sweepers downloads by day](figures/space-sweepers-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.40 | 10.05 | 45.55 | 27.98 | 1.23 | 1.26 |

### Cumulative network infrastructure

[![Space Sweepers cumulative map](figures/space-sweepers-carto.png)](figures/space-sweepers-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/space-sweepers-data-ge-1080p.webp)](figures/space-sweepers-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/space-sweepers-data-lt-1080p.webp)](figures/space-sweepers-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
