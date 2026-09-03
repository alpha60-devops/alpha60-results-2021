---
layout: default
title: "dont-look-up Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# dont-look-up sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Don't Look Up |
| Collection key | `dont-look-up` |
| imdb_id | [tt11286314](https://www.imdb.com/title/tt11286314/) |
| wikipedia_url | [Don't Look Up](https://en.wikipedia.org/wiki/Don%27t_Look_Up) |
| Sample dates | 2021-12-24-to-2022-04-07 |
| Sample days | 105 |
| BTIH count | 205 |
| Unique BTIH count | 173 |
| Downloaders total | 15,407,604 |
| Uploaders total | 6,786,268 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-12-24 to 2022-04-07 (105 days)
- Cache Day products: 105
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Don't Look Up collection size histogram](figures/dont-look-up-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/dont-look-up-downloads-by-week-dont-look-up-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![dont-look-up downloads by day](figures/dont-look-up-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.62 | 9.49 | 22.43 | 54.43 | 1.20 | 0.67 |

### Cumulative network infrastructure

[![Don't Look Up cumulative map](figures/dont-look-up-carto.png)](figures/dont-look-up-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/dont-look-up-data-ge-1080p.webp)](figures/dont-look-up-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/dont-look-up-data-lt-1080p.webp)](figures/dont-look-up-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
