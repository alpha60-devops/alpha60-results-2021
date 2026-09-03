---
layout: default
title: "q-force-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# q-force-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Q-Force |
| Collection key | `q-force-01` |
| imdb_id | [tt10140028](https://www.imdb.com/title/tt10140028/) |
| wikipedia_url | [Q-Force](https://en.wikipedia.org/wiki/Q-Force) |
| Sample dates | 2021-09-02-to-2021-11-10 |
| Sample days | 70 |
| BTIH count | 97 |
| Unique BTIH count | 94 |
| Downloaders total | 652,894 |
| Uploaders total | 40,667 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-09-02 to 2021-11-10 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Q-Force collection size histogram](figures/q-force-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/q-force-01-downloads-by-week-q-force-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![q-force-01 downloads by day](figures/q-force-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.60 | 31.45 | 17.52 | 30.69 | 1.28 | 8.12 |

### Cumulative network infrastructure

[![Q-Force cumulative map](figures/q-force-01-carto.png)](figures/q-force-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/q-force-01-data-ge-1080p.webp)](figures/q-force-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/q-force-01-data-lt-1080p.webp)](figures/q-force-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
