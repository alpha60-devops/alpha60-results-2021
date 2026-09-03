---
layout: default
title: "prisoners-of-the-ghostland Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# prisoners-of-the-ghostland sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Prisoners of the Ghostland |
| Collection key | `prisoners-of-the-ghostland` |
| imdb_id | [tt6372694](https://www.imdb.com/title/tt6372694/) |
| wikipedia_url | [Prisoners of the Ghostland](https://en.wikipedia.org/wiki/Prisoners_of_the_Ghostland) |
| Sample dates | 2021-09-15-to-2021-11-23 |
| Sample days | 70 |
| BTIH count | 145 |
| Unique BTIH count | 127 |
| Downloaders total | 3,519,336 |
| Uploaders total | 1,038,303 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-09-15 to 2021-11-23 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Prisoners of the Ghostland collection size histogram](figures/prisoners-of-the-ghostland-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/prisoners-of-the-ghostland-downloads-by-week-prisoners-of-the-ghostland-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![prisoners-of-the-ghostland downloads by day](figures/prisoners-of-the-ghostland-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 10.78 | 19.19 | 25.40 | 33.17 | 2.31 | 1.95 |

### Cumulative network infrastructure

[![Prisoners of the Ghostland cumulative map](figures/prisoners-of-the-ghostland-carto.png)](figures/prisoners-of-the-ghostland-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/prisoners-of-the-ghostland-data-ge-1080p.webp)](figures/prisoners-of-the-ghostland-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/prisoners-of-the-ghostland-data-lt-1080p.webp)](figures/prisoners-of-the-ghostland-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
