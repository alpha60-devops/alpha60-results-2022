---
layout: default
title: "raised-by-wolves-201 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# raised-by-wolves-201 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Raised by Wolves |
| Collection key | `raised-by-wolves-201` |
| imdb_id | [tt9170108](https://www.imdb.com/title/tt9170108/) |
| wikipedia_url | [Raised by Wolves (American TV series)](https://en.wikipedia.org/wiki/Raised_by_Wolves_(American_TV_series)) |
| Sample dates | 2022-02-03-to-2022-04-13 |
| Sample days | 70 |
| BTIH count | 134 |
| Unique BTIH count | 107 |
| Downloaders total | 3,068,265 |
| Uploaders total | 896,007 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:19Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/raised-by-wolves-201.xz`
- Hour directories: 1661
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (1 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-03-27 01:00`, resumed `2022-03-27 03:00` — missing 1 hour(s)

## 3. Media objects file size histogram

![Raised by Wolves collection size histogram](figures/raised-by-wolves-201-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/raised-by-wolves-201-downloads-by-week-raised-by-wolves-201-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![raised-by-wolves-201 downloads by day](figures/raised-by-wolves-201-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.48 | 20.24 | 18.58 | 45.63 | 3.96 | 0.63 |

### Cumulative network infrastructure

[![Raised by Wolves cumulative map](figures/raised-by-wolves-201-carto.png)](figures/raised-by-wolves-201-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/raised-by-wolves-201-data-ge-1080p.webp)](figures/raised-by-wolves-201-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/raised-by-wolves-201-data-lt-1080p.webp)](figures/raised-by-wolves-201-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
