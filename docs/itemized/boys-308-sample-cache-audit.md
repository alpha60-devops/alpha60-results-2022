---
layout: default
title: "boys-308 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# boys-308 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Boys |
| Collection key | `boys-308` |
| imdb_id | [tt1190634](https://www.imdb.com/title/tt1190634/) |
| wikipedia_url | [The Boys (TV series)](https://en.wikipedia.org/wiki/The_Boys_(TV_series)) |
| Sample dates | 2022-07-08-to-2022-11-03 |
| Sample days | 119 |
| BTIH count | 237 |
| Unique BTIH count | 211 |
| Downloaders total | 6,904,640 |
| Uploaders total | 2,276,701 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:12Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/boys-308.xz`
- Hour directories: 2828
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 14 (14 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-07-08 22:00`, resumed `2022-07-09 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-09 22:00`, resumed `2022-07-10 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-10 22:00`, resumed `2022-07-11 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-11 22:00`, resumed `2022-07-12 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-12 22:00`, resumed `2022-07-13 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-13 22:00`, resumed `2022-07-14 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-14 22:00`, resumed `2022-07-15 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-15 22:00`, resumed `2022-07-16 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-16 22:00`, resumed `2022-07-17 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-17 22:00`, resumed `2022-07-18 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-18 22:00`, resumed `2022-07-19 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-19 22:00`, resumed `2022-07-20 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-20 22:00`, resumed `2022-07-21 00:00` — missing 1 hour(s)
- hourly gap: last `2022-07-21 22:00`, resumed `2022-07-22 00:00` — missing 1 hour(s)

## 3. Media objects file size histogram

![The Boys collection size histogram](figures/boys-308-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/boys-308-downloads-by-week-boys-308-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![boys-308 downloads by day](figures/boys-308-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.63 | 17.46 | 23.86 | 46.63 | 2.10 | 0.82 |

### Cumulative network infrastructure

[![The Boys cumulative map](figures/boys-308-carto.png)](figures/boys-308-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/boys-308-data-ge-1080p.webp)](figures/boys-308-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/boys-308-data-lt-1080p.webp)](figures/boys-308-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
