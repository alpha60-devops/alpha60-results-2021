---
layout: default
title: "mother-android Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# mother-android sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Mother/Android |
| Collection key | `mother-android` |
| imdb_id | [tt13029044](https://www.imdb.com/title/tt13029044/) |
| wikipedia_url | [Android](https://en.wikipedia.org/wiki/Mother/Android) |
| Sample dates | 2021-12-17-to-2022-02-25 |
| Sample days | 71 |
| BTIH count | 109 |
| Unique BTIH count | 82 |
| Downloaders total | 2,532,094 |
| Uploaders total | 840,179 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-12-17 to 2022-02-25 (71 days)
- Cache Day products: 71
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Mother/Android collection size histogram](figures/mother-android-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/mother-android-downloads-by-week-mother-android-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![mother-android downloads by day](figures/mother-android-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 12.74 | 20.00 | 21.37 | 36.54 | 2.34 | 0.67 |

### Cumulative network infrastructure

[![Mother/Android cumulative map](figures/mother-android-carto.png)](figures/mother-android-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/mother-android-data-ge-1080p.webp)](figures/mother-android-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/mother-android-data-lt-1080p.webp)](figures/mother-android-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
