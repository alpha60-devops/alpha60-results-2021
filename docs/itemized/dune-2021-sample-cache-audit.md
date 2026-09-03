---
layout: default
title: "dune-2021 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# dune-2021 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Dune 2021: Part One |
| Collection key | `dune-2021` |
| imdb_id | [tt1160419](https://www.imdb.com/title/tt1160419/) |
| wikipedia_url | [Dune (2021 film)](https://en.wikipedia.org/wiki/Dune_(2021_film)) |
| Sample dates | 2021-10-18-to-2022-04-17 |
| Sample days | 182 |
| BTIH count | 368 |
| Unique BTIH count | 320 |
| Downloaders total | 37,177,029 |
| Uploaders total | 13,541,903 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-10-18 to 2022-04-17 (182 days)
- Cache Day products: 182
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Dune 2021: Part One collection size histogram](figures/dune-2021-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/dune-2021-downloads-by-week-dune-2021-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![dune-2021 downloads by day](figures/dune-2021-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.46 | 14.87 | 25.12 | 42.41 | 2.16 | 0.68 |

### Cumulative network infrastructure

[![Dune 2021: Part One cumulative map](figures/dune-2021-carto.png)](figures/dune-2021-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/dune-2021-data-ge-1080p.webp)](figures/dune-2021-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/dune-2021-data-lt-1080p.webp)](figures/dune-2021-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
