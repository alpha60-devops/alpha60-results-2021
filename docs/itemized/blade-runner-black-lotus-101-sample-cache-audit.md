---
layout: default
title: "blade-runner-black-lotus-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# blade-runner-black-lotus-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Blade Runner Black Lotus |
| Collection key | `blade-runner-black-lotus-101` |
| imdb_id | [tt9359796](https://www.imdb.com/title/tt9359796/) |
| wikipedia_url | [Blade Runner: Black Lotus](https://en.wikipedia.org/wiki/Blade_Runner:_Black_Lotus) |
| Sample dates | 2021-11-14-to-2022-01-22 |
| Sample days | 70 |
| BTIH count | 117 |
| Unique BTIH count | 84 |
| Downloaders total | 1,169,311 |
| Uploaders total | 199,595 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-11-14 to 2022-01-22 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Blade Runner Black Lotus collection size histogram](figures/blade-runner-black-lotus-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/blade-runner-black-lotus-101-downloads-by-week-blade-runner-black-lotus-101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![blade-runner-black-lotus-101 downloads by day](figures/blade-runner-black-lotus-101-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.83 | 26.56 | 19.13 | 42.62 | 2.58 | 1.28 |

### Cumulative network infrastructure

[![Blade Runner Black Lotus cumulative map](figures/blade-runner-black-lotus-101-carto.png)](figures/blade-runner-black-lotus-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/blade-runner-black-lotus-101-data-ge-1080p.webp)](figures/blade-runner-black-lotus-101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/blade-runner-black-lotus-101-data-lt-1080p.webp)](figures/blade-runner-black-lotus-101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
