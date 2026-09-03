---
layout: default
title: "godzilla-vs-kong Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# godzilla-vs-kong sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Godzilla vs. Kong |
| Collection key | `godzilla-vs-kong` |
| imdb_id | [tt5034838](https://www.imdb.com/title/tt5034838/) |
| wikipedia_url | [Godzilla vs. Kong](https://en.wikipedia.org/wiki/Godzilla_vs._Kong) |
| Sample dates | 2021-03-31-to-2021-09-28 |
| Sample days | 182 |
| BTIH count | 307 |
| Unique BTIH count | 276 |
| Downloaders total | 48,466,070 |
| Uploaders total | 11,479,839 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-03-31 to 2021-09-28 (182 days)
- Cache Day products: 181
- Sparse Day indices: 1
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index 113: `2021-07-21`

## 3. Media objects file size histogram

![Godzilla vs. Kong collection size histogram](figures/godzilla-vs-kong-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/godzilla-vs-kong-downloads-by-week-godzilla-vs-kong-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![godzilla-vs-kong downloads by day](figures/godzilla-vs-kong-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.38 | 29.17 | 30.31 | 24.49 | 1.52 | 5.65 |

### Cumulative network infrastructure

[![Godzilla vs. Kong cumulative map](figures/godzilla-vs-kong-carto.png)](figures/godzilla-vs-kong-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/godzilla-vs-kong-data-ge-1080p.webp)](figures/godzilla-vs-kong-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/godzilla-vs-kong-data-lt-1080p.webp)](figures/godzilla-vs-kong-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
