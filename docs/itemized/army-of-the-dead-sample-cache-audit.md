---
layout: default
title: "army-of-the-dead Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# army-of-the-dead sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Army of the Dead |
| Collection key | `army-of-the-dead` |
| imdb_id | [tt0993840](https://www.imdb.com/title/tt0993840/) |
| wikipedia_url | [Army of the Dead](https://en.wikipedia.org/wiki/Army_of_the_Dead) |
| Sample dates | 2021-05-21-to-2021-09-02 |
| Sample days | 105 |
| BTIH count | 164 |
| Unique BTIH count | 150 |
| Downloaders total | 12,851,257 |
| Uploaders total | 2,428,318 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-05-21 to 2021-09-02 (105 days)
- Cache Day products: 105
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Army of the Dead collection size histogram](figures/army-of-the-dead-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/army-of-the-dead-downloads-by-week-army-of-the-dead-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![army-of-the-dead downloads by day](figures/army-of-the-dead-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.06 | 25.46 | 25.40 | 30.68 | 1.38 | 6.77 |

### Cumulative network infrastructure

[![Army of the Dead cumulative map](figures/army-of-the-dead-carto.png)](figures/army-of-the-dead-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/army-of-the-dead-data-ge-1080p.webp)](figures/army-of-the-dead-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/army-of-the-dead-data-lt-1080p.webp)](figures/army-of-the-dead-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
