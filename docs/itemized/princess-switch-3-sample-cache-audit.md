---
layout: default
title: "princess-switch-3 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# princess-switch-3 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Princess Switch 3 |
| Collection key | `princess-switch-3` |
| imdb_id | [tt14731142](https://www.imdb.com/title/tt14731142/) |
| wikipedia_url | [The Princess Switch 3: Romancing the Star](https://en.wikipedia.org/wiki/The_Princess_Switch_3:_Romancing_the_Star) |
| Sample dates | 2021-11-19-to-2022-01-27 |
| Sample days | 70 |
| BTIH count | 69 |
| Unique BTIH count | 53 |
| Downloaders total | 761,648 |
| Uploaders total | 138,466 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-11-19 to 2022-01-27 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![The Princess Switch 3 collection size histogram](figures/princess-switch-3-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/princess-switch-3-downloads-by-week-princess-switch-3-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![princess-switch-3 downloads by day](figures/princess-switch-3-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 13.91 | 14.97 | 19.30 | 40.14 | 1.08 | 0.70 |

### Cumulative network infrastructure

[![The Princess Switch 3 cumulative map](figures/princess-switch-3-carto.png)](figures/princess-switch-3-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/princess-switch-3-data-ge-1080p.webp)](figures/princess-switch-3-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/princess-switch-3-data-lt-1080p.webp)](figures/princess-switch-3-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
