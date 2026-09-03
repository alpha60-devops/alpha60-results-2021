---
layout: default
title: "one-night-in-miami Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# one-night-in-miami sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | One Night In Miami |
| Collection key | `one-night-in-miami` |
| imdb_id | [tt10612922](https://www.imdb.com/title/tt10612922/) |
| wikipedia_url | [One Night in Miami...](https://en.wikipedia.org/wiki/One_Night_in_Miami...) |
| Sample dates | 2021-01-15-to-2021-03-25 |
| Sample days | 70 |
| BTIH count | 94 |
| Unique BTIH count | 62 |
| Downloaders total | 4,272,865 |
| Uploaders total | 580,824 |
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

![One Night In Miami collection size histogram](figures/one-night-in-miami-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/one-night-in-miami-downloads-by-week-one-night-in-miami-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![one-night-in-miami downloads by day](figures/one-night-in-miami-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 9.42 | 36.11 | 19.14 | 18.71 | 1.81 | 10.43 |

### Cumulative network infrastructure

[![One Night In Miami cumulative map](figures/one-night-in-miami-carto.png)](figures/one-night-in-miami-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/one-night-in-miami-data-ge-1080p.webp)](figures/one-night-in-miami-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/one-night-in-miami-data-lt-1080p.webp)](figures/one-night-in-miami-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
