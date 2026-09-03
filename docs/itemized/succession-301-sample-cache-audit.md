---
layout: default
title: "succession-301 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# succession-301 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Succession |
| Collection key | `succession-301` |
| imdb_id | [tt7660850](https://www.imdb.com/title/tt7660850/) |
| wikipedia_url | [Succession (TV series)](https://en.wikipedia.org/wiki/Succession_(TV_series)) |
| Sample dates | 2021-10-18-to-2021-12-26 |
| Sample days | 70 |
| BTIH count | 67 |
| Unique BTIH count | 60 |
| Downloaders total | 1,510,041 |
| Uploaders total | 408,259 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-10-18 to 2021-12-26 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Succession collection size histogram](figures/succession-301-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/succession-301-downloads-by-week-succession-301-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![succession-301 downloads by day](figures/succession-301-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.40 | 24.85 | 16.20 | 39.73 | 2.96 | 3.05 |

### Cumulative network infrastructure

[![Succession cumulative map](figures/succession-301-carto.png)](figures/succession-301-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/succession-301-data-ge-1080p.webp)](figures/succession-301-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/succession-301-data-lt-1080p.webp)](figures/succession-301-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
