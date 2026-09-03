---
layout: default
title: "coming-2-america Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# coming-2-america sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Coming 2 America |
| Collection key | `coming-2-america` |
| imdb_id | [tt6802400](https://www.imdb.com/title/tt6802400/) |
| wikipedia_url | [Coming 2 America](https://en.wikipedia.org/wiki/Coming_2_America) |
| Sample dates | 2021-03-05-to-2021-03-27 |
| Sample days | 23 |
| BTIH count | 144 |
| Unique BTIH count | 122 |
| Downloaders total | 4,889,254 |
| Uploaders total | 1,510,336 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-03-05 to 2021-03-27 (23 days)
- Cache Day products: 23
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Coming 2 America collection size histogram](figures/coming-2-america-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/coming-2-america-downloads-by-week-coming-2-america-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![coming-2-america downloads by day](figures/coming-2-america-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 21.98 | 19.93 | 18.23 | 27.78 | 3.39 | 1.53 |

### Cumulative network infrastructure

[![Coming 2 America cumulative map](figures/coming-2-america-carto.png)](figures/coming-2-america-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/coming-2-america-data-ge-1080p.webp)](figures/coming-2-america-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/coming-2-america-data-lt-1080p.webp)](figures/coming-2-america-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
