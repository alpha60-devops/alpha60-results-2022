---
layout: default
title: "andor-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# andor-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Andor |
| Collection key | `andor-101` |
| imdb_id | [tt9253284](https://www.imdb.com/title/tt9253284/) |
| wikipedia_url | [Andor](https://en.wikipedia.org/wiki/Andor) |
| Sample dates | 2022-09-21-to-2023-03-21 |
| Sample days | 182 |
| BTIH count | 405 |
| Unique BTIH count | 347 |
| Downloaders total | 15,259,681 |
| Uploaders total | 5,064,577 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:11Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/andor-101.xz`
- Hour directories: 4156
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 2 (196 missing hours)
- Missing days: 8

### Sample archive discontinuities

- hourly gap: last `2022-12-18 22:00`, resumed `2022-12-20 03:18` — missing 28 hour(s)
- hourly gap: last `2023-02-14 23:00`, resumed `2023-02-22 00:00` — missing 168 hour(s)
- missing day: `2022-12-19`
- missing day: `2023-02-15`
- missing day: `2023-02-16`
- missing day: `2023-02-17`
- missing day: `2023-02-18`
- missing day: `2023-02-19`
- missing day: `2023-02-20`
- missing day: `2023-02-21`

## 3. Media objects file size histogram

![Andor collection size histogram](figures/andor-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/andor-101-downloads-by-week-andor-101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![andor-101 downloads by day](figures/andor-101-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.96 | 21.67 | 19.76 | 47.26 | 3.04 | 0.66 |

### Cumulative network infrastructure

[![Andor cumulative map](figures/andor-101-carto.png)](figures/andor-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/andor-101-data-ge-1080p.webp)](figures/andor-101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/andor-101-data-lt-1080p.webp)](figures/andor-101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
