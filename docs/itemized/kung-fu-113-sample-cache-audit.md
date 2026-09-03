---
layout: default
title: "kung-fu-113 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# kung-fu-113 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Kung Fu 2021 |
| Collection key | `kung-fu-113` |
| imdb_id | [tt7475590](https://www.imdb.com/title/tt7475590/) |
| wikipedia_url | [Kung Fu (2021 TV series)](https://en.wikipedia.org/wiki/Kung_Fu_(2021_TV_series)) |
| Sample dates | 2021-07-22-to-2021-09-29 |
| Sample days | 70 |
| BTIH count | 74 |
| Unique BTIH count | 61 |
| Downloaders total | 2,843,980 |
| Uploaders total | 105,539 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-07-22 to 2021-09-29 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Kung Fu 2021 collection size histogram](figures/kung-fu-113-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/kung-fu-113-downloads-by-week-kung-fu-113-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![kung-fu-113 downloads by day](figures/kung-fu-113-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.45 | 36.86 | 18.52 | 24.67 | 1.55 | 11.22 |

### Cumulative network infrastructure

[![Kung Fu 2021 cumulative map](figures/kung-fu-113-carto.png)](figures/kung-fu-113-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/kung-fu-113-data-ge-1080p.webp)](figures/kung-fu-113-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/kung-fu-113-data-lt-1080p.webp)](figures/kung-fu-113-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
