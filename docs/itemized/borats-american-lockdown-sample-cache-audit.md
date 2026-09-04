---
layout: default
title: "borats-american-lockdown Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# borats-american-lockdown sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Borats American Lockdown |
| Collection key | `borats-american-lockdown` |
| imdb_id | [tt14532412](https://www.imdb.com/title/tt14532412/) |
| wikipedia_url | UNAVAILABLE — no English Wikipedia page exists |
| Sample dates | 2021-05-25-to-2021-08-02 |
| Sample days | 70 |
| BTIH count | 131 |
| Unique BTIH count | 108 |
| Downloaders total | 2,591,070 |
| Uploaders total | 57,253 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-05-25 to 2021-08-02 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Borats American Lockdown collection size histogram](figures/borats-american-lockdown-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/borats-american-lockdown-downloads-by-week-borats-american-lockdown-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![borats-american-lockdown downloads by day](figures/borats-american-lockdown-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.67 | 39.58 | 18.99 | 21.65 | 1.74 | 11.86 |

### Cumulative network infrastructure

[![Borats American Lockdown cumulative map](figures/borats-american-lockdown-carto.png)](figures/borats-american-lockdown-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/borats-american-lockdown-data-ge-1080p.webp)](figures/borats-american-lockdown-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/borats-american-lockdown-data-lt-1080p.webp)](figures/borats-american-lockdown-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
