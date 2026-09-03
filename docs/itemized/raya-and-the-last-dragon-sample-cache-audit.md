---
layout: default
title: "raya-and-the-last-dragon Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# raya-and-the-last-dragon sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Raya & The Last Dragon |
| Collection key | `raya-and-the-last-dragon` |
| imdb_id | [tt5109280](https://www.imdb.com/title/tt5109280/) |
| wikipedia_url | [Raya and the Last Dragon](https://en.wikipedia.org/wiki/Raya_and_the_Last_Dragon) |
| Sample dates | 2021-03-05-to-2021-09-02 |
| Sample days | 182 |
| BTIH count | 195 |
| Unique BTIH count | 175 |
| Downloaders total | 35,229,856 |
| Uploaders total | 9,716,616 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-03-05 to 2021-09-02 (182 days)
- Cache Day products: 182
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Raya & The Last Dragon collection size histogram](figures/raya-and-the-last-dragon-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/raya-and-the-last-dragon-downloads-by-week-raya-and-the-last-dragon-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![raya-and-the-last-dragon downloads by day](figures/raya-and-the-last-dragon-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.03 | 25.59 | 26.62 | 29.78 | 1.65 | 5.57 |

### Cumulative network infrastructure

[![Raya & The Last Dragon cumulative map](figures/raya-and-the-last-dragon-carto.png)](figures/raya-and-the-last-dragon-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/raya-and-the-last-dragon-data-ge-1080p.webp)](figures/raya-and-the-last-dragon-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/raya-and-the-last-dragon-data-lt-1080p.webp)](figures/raya-and-the-last-dragon-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
