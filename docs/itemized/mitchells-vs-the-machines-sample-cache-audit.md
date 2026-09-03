---
layout: default
title: "mitchells-vs-the-machines Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# mitchells-vs-the-machines sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Mitchells vs The Machines |
| Collection key | `mitchells-vs-the-machines` |
| imdb_id | [tt7979580](https://www.imdb.com/title/tt7979580/) |
| wikipedia_url | [The Mitchells vs. the Machines](https://en.wikipedia.org/wiki/The_Mitchells_vs._the_Machines) |
| Sample dates | 2021-05-01-to-2021-07-09 |
| Sample days | 70 |
| BTIH count | 118 |
| Unique BTIH count | 83 |
| Downloaders total | 11,036,594 |
| Uploaders total | 2,777,975 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-05-01 to 2021-07-09 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![The Mitchells vs The Machines collection size histogram](figures/mitchells-vs-the-machines-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/mitchells-vs-the-machines-downloads-by-week-mitchells-vs-the-machines-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![mitchells-vs-the-machines downloads by day](figures/mitchells-vs-the-machines-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.44 | 23.78 | 25.11 | 28.94 | 1.64 | 6.07 |

### Cumulative network infrastructure

[![The Mitchells vs The Machines cumulative map](figures/mitchells-vs-the-machines-carto.png)](figures/mitchells-vs-the-machines-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/mitchells-vs-the-machines-data-ge-1080p.webp)](figures/mitchells-vs-the-machines-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/mitchells-vs-the-machines-data-lt-1080p.webp)](figures/mitchells-vs-the-machines-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
