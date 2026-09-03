---
layout: default
title: "wandavision-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# wandavision-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | WandaVision |
| Collection key | `wandavision-101` |
| imdb_id | [tt9140560](https://www.imdb.com/title/tt9140560/) |
| wikipedia_url | [WandaVision](https://en.wikipedia.org/wiki/WandaVision) |
| Sample dates | 2021-01-15-to-2021-03-25 |
| Sample days | 70 |
| BTIH count | 170 |
| Unique BTIH count | 142 |
| Downloaders total | 12,961,778 |
| Uploaders total | 2,897,568 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-01-15 to 2021-03-25 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![WandaVision collection size histogram](figures/wandavision-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/wandavision-101-downloads-by-week-wandavision-101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![wandavision-101 downloads by day](figures/wandavision-101-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.94 | 31.01 | 28.36 | 21.46 | 2.51 | 6.30 |

### Cumulative network infrastructure

[![WandaVision cumulative map](figures/wandavision-101-carto.png)](figures/wandavision-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/wandavision-101-data-ge-1080p.webp)](figures/wandavision-101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/wandavision-101-data-lt-1080p.webp)](figures/wandavision-101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
