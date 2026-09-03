---
layout: default
title: "summer-of-soul Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# summer-of-soul sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Summer of Soul |
| Collection key | `summer-of-soul` |
| imdb_id | [tt7378922](https://www.imdb.com/title/tt7378922/) |
| wikipedia_url | [Summer of Soul](https://en.wikipedia.org/wiki/Summer_of_Soul) |
| Sample dates | 2021-07-03-to-2021-09-10 |
| Sample days | 70 |
| BTIH count | 29 |
| Unique BTIH count | 22 |
| Downloaders total | 664,229 |
| Uploaders total | 58,500 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-07-03 to 2021-09-10 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Summer of Soul collection size histogram](figures/summer-of-soul-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/summer-of-soul-downloads-by-week-summer-of-soul-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![summer-of-soul downloads by day](figures/summer-of-soul-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.91 | 34.51 | 15.02 | 22.81 | 1.78 | 8.20 |

### Cumulative network infrastructure

[![Summer of Soul cumulative map](figures/summer-of-soul-carto.png)](figures/summer-of-soul-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/summer-of-soul-data-ge-1080p.webp)](figures/summer-of-soul-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/summer-of-soul-data-lt-1080p.webp)](figures/summer-of-soul-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
