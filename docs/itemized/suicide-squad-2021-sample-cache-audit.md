---
layout: default
title: "suicide-squad-2021 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# suicide-squad-2021 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Suicide Squad |
| Collection key | `suicide-squad-2021` |
| imdb_id | [tt6334354](https://www.imdb.com/title/tt6334354/) |
| wikipedia_url | [The Suicide Squad (film)](https://en.wikipedia.org/wiki/The_Suicide_Squad_(film)) |
| Sample dates | 2021-08-06-to-2022-02-03 |
| Sample days | 182 |
| BTIH count | 306 |
| Unique BTIH count | 280 |
| Downloaders total | 31,993,818 |
| Uploaders total | 7,987,300 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-08-06 to 2022-02-03 (182 days)
- Cache Day products: 181
- Sparse Day indices: 1
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index 178: `2022-01-30`

## 3. Media objects file size histogram

![Suicide Squad collection size histogram](figures/suicide-squad-2021-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/suicide-squad-2021-downloads-by-week-suicide-squad-2021-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![suicide-squad-2021 downloads by day](figures/suicide-squad-2021-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.60 | 22.00 | 26.64 | 31.91 | 1.91 | 3.53 |

### Cumulative network infrastructure

[![Suicide Squad cumulative map](figures/suicide-squad-2021-carto.png)](figures/suicide-squad-2021-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/suicide-squad-2021-data-ge-1080p.webp)](figures/suicide-squad-2021-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/suicide-squad-2021-data-lt-1080p.webp)](figures/suicide-squad-2021-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
