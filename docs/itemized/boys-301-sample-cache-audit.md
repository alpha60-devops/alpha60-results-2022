---
layout: default
title: "boys-301 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# boys-301 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Boys |
| Collection key | `boys-301` |
| imdb_id | [tt1190634](https://www.imdb.com/title/tt1190634/) |
| wikipedia_url | [The Boys (TV series)](https://en.wikipedia.org/wiki/The_Boys_(TV_series)) |
| Sample dates | 2022-06-03-to-2022-09-22 |
| Sample days | 112 |
| BTIH count | 318 |
| Unique BTIH count | 273 |
| Downloaders total | 15,936,745 |
| Uploaders total | 5,539,530 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:12Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/boys-301.xz`
- Hour directories: 2664
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (21 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-08-06 23:00`, resumed `2022-08-07 21:00` — missing 21 hour(s)

## 3. Media objects file size histogram

![The Boys collection size histogram](figures/boys-301-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/boys-301-downloads-by-week-boys-301-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![boys-301 downloads by day](figures/boys-301-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 7.28 | 21.13 | 29.12 | 34.91 | 3.53 | 0.60 |

### Cumulative network infrastructure

[![The Boys cumulative map](figures/boys-301-carto.png)](figures/boys-301-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/boys-301-data-ge-1080p.webp)](figures/boys-301-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/boys-301-data-lt-1080p.webp)](figures/boys-301-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
