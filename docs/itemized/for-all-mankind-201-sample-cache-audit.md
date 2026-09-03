---
layout: default
title: "for-all-mankind-201 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# for-all-mankind-201 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | For All Mankind |
| Collection key | `for-all-mankind-201` |
| imdb_id | [tt7772588](https://www.imdb.com/title/tt7772588/) |
| wikipedia_url | [For All Mankind (TV series)](https://en.wikipedia.org/wiki/For_All_Mankind_(TV_series)) |
| Sample dates | 2021-02-19-to-2021-04-29 |
| Sample days | 70 |
| BTIH count | 75 |
| Unique BTIH count | 64 |
| Downloaders total | 1,672,433 |
| Uploaders total | 171,266 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-02-19 to 2021-04-29 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![For All Mankind collection size histogram](figures/for-all-mankind-201-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/for-all-mankind-201-downloads-by-week-for-all-mankind-201-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![for-all-mankind-201 downloads by day](figures/for-all-mankind-201-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.76 | 38.03 | 18.46 | 24.04 | 2.40 | 10.40 |

### Cumulative network infrastructure

[![For All Mankind cumulative map](figures/for-all-mankind-201-carto.png)](figures/for-all-mankind-201-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/for-all-mankind-201-data-ge-1080p.webp)](figures/for-all-mankind-201-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/for-all-mankind-201-data-lt-1080p.webp)](figures/for-all-mankind-201-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
