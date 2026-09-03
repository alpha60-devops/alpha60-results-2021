---
layout: default
title: "ted-lasso-201 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# ted-lasso-201 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Ted Lasso |
| Collection key | `ted-lasso-201` |
| imdb_id | [tt10986410](https://www.imdb.com/title/tt10986410/) |
| wikipedia_url | [Ted Lasso](https://en.wikipedia.org/wiki/Ted_Lasso) |
| Sample dates | 2021-07-23-to-2021-09-30 |
| Sample days | 70 |
| BTIH count | 83 |
| Unique BTIH count | 68 |
| Downloaders total | 4,014,855 |
| Uploaders total | 479,453 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-07-23 to 2021-09-30 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Ted Lasso collection size histogram](figures/ted-lasso-201-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/ted-lasso-201-downloads-by-week-ted-lasso-201-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![ted-lasso-201 downloads by day](figures/ted-lasso-201-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.20 | 35.99 | 17.81 | 27.10 | 2.37 | 9.14 |

### Cumulative network infrastructure

[![Ted Lasso cumulative map](figures/ted-lasso-201-carto.png)](figures/ted-lasso-201-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/ted-lasso-201-data-ge-1080p.webp)](figures/ted-lasso-201-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/ted-lasso-201-data-lt-1080p.webp)](figures/ted-lasso-201-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
