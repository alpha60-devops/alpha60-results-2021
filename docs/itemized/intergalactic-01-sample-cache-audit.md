---
layout: default
title: "intergalactic-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# intergalactic-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Intergalactic |
| Collection key | `intergalactic-01` |
| imdb_id | [tt9849186](https://www.imdb.com/title/tt9849186/) |
| wikipedia_url | [Intergalactic (TV series)](https://en.wikipedia.org/wiki/Intergalactic_(TV_series)) |
| Sample dates | 2021-05-01-to-2021-07-09 |
| Sample days | 70 |
| BTIH count | 167 |
| Unique BTIH count | 167 |
| Downloaders total | 5,903,851 |
| Uploaders total | 225,008 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-05-01 to 2021-07-09 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Intergalactic collection size histogram](figures/intergalactic-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/intergalactic-01-downloads-by-week-intergalactic-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![intergalactic-01 downloads by day](figures/intergalactic-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.44 | 41.18 | 18.61 | 22.36 | 1.73 | 12.02 |

### Cumulative network infrastructure

[![Intergalactic cumulative map](figures/intergalactic-01-carto.png)](figures/intergalactic-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/intergalactic-01-data-ge-1080p.webp)](figures/intergalactic-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/intergalactic-01-data-lt-1080p.webp)](figures/intergalactic-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
