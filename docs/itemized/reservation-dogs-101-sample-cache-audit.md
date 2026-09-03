---
layout: default
title: "reservation-dogs-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# reservation-dogs-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Reservation Dogs |
| Collection key | `reservation-dogs-101` |
| imdb_id | [tt13623580](https://www.imdb.com/title/tt13623580/) |
| wikipedia_url | [Reservation Dogs](https://en.wikipedia.org/wiki/Reservation_Dogs) |
| Sample dates | 2021-08-09-to-2021-10-17 |
| Sample days | 70 |
| BTIH count | 86 |
| Unique BTIH count | 75 |
| Downloaders total | 2,914,092 |
| Uploaders total | 266,638 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-08-09 to 2021-10-17 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Reservation Dogs collection size histogram](figures/reservation-dogs-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/reservation-dogs-101-downloads-by-week-reservation-dogs-101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![reservation-dogs-101 downloads by day](figures/reservation-dogs-101-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.93 | 37.13 | 17.85 | 26.78 | 2.66 | 9.34 |

### Cumulative network infrastructure

[![Reservation Dogs cumulative map](figures/reservation-dogs-101-carto.png)](figures/reservation-dogs-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/reservation-dogs-101-data-ge-1080p.webp)](figures/reservation-dogs-101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/reservation-dogs-101-data-lt-1080p.webp)](figures/reservation-dogs-101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
