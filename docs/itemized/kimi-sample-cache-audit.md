---
layout: default
title: "kimi Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# kimi sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Kimi |
| Collection key | `kimi` |
| imdb_id | [tt14128670](https://www.imdb.com/title/tt14128670/) |
| wikipedia_url | [Kimi (film)](https://en.wikipedia.org/wiki/Kimi_(film)) |
| Sample dates | 2022-02-11-to-2022-06-02 |
| Sample days | 112 |
| BTIH count | 137 |
| Unique BTIH count | 103 |
| Downloaders total | 5,216,721 |
| Uploaders total | 1,910,379 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:16Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/kimi.xz`
- Hour directories: 2587
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 2 (99 missing hours)
- Missing days: 3

### Sample archive discontinuities

- hourly gap: last `2022-03-07 22:06`, resumed `2022-03-08 07:06` — missing 8 hour(s)
- hourly gap: last `2022-03-18 22:06`, resumed `2022-03-22 18:06` — missing 91 hour(s)
- missing day: `2022-03-19`
- missing day: `2022-03-20`
- missing day: `2022-03-21`

## 3. Media objects file size histogram

![Kimi collection size histogram](figures/kimi-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/kimi-downloads-by-week-kimi-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![kimi downloads by day](figures/kimi-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 14.40 | 13.28 | 23.39 | 39.42 | 2.05 | 0.76 |

### Cumulative network infrastructure

[![Kimi cumulative map](figures/kimi-carto.png)](figures/kimi-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/kimi-data-ge-1080p.webp)](figures/kimi-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/kimi-data-lt-1080p.webp)](figures/kimi-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
