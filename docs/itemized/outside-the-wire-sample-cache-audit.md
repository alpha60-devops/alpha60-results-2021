---
layout: default
title: "outside-the-wire Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# outside-the-wire sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Outside The Wire |
| Collection key | `outside-the-wire` |
| imdb_id | [tt10451914](https://www.imdb.com/title/tt10451914/) |
| wikipedia_url | [Outside the Wire](https://en.wikipedia.org/wiki/Outside_the_Wire) |
| Sample dates | 2021-01-15-to-2021-03-25 |
| Sample days | 70 |
| BTIH count | 129 |
| Unique BTIH count | 108 |
| Downloaders total | 7,196,232 |
| Uploaders total | 3,010,308 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-03T11:11:21Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2021-01-15 to 2021-03-25 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Outside The Wire collection size histogram](figures/outside-the-wire-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/outside-the-wire-downloads-by-week-outside-the-wire-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![outside-the-wire downloads by day](figures/outside-the-wire-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 10.37 | 7.73 | 24.18 | 48.55 | 1.29 | 0.59 |

### Cumulative network infrastructure

[![Outside The Wire cumulative map](figures/outside-the-wire-carto.png)](figures/outside-the-wire-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/outside-the-wire-data-ge-1080p.webp)](figures/outside-the-wire-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/outside-the-wire-data-lt-1080p.webp)](figures/outside-the-wire-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
