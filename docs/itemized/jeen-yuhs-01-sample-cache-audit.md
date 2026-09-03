---
layout: default
title: "jeen-yuhs-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# jeen-yuhs-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Jeen Yuhs |
| Collection key | `jeen-yuhs-01` |
| imdb_id | [tt14599438](https://www.imdb.com/title/tt14599438/) |
| wikipedia_url | [Jeen-Yuhs](https://en.wikipedia.org/wiki/Jeen-Yuhs) |
| Sample dates | 2022-03-04-to-2022-05-19 |
| Sample days | 77 |
| BTIH count | 78 |
| Unique BTIH count | 66 |
| Downloaders total | 818,763 |
| Uploaders total | 151,149 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:16Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/jeen-yuhs-01.xz`
- Hour directories: 1845
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (3 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-04-11 21:03`, resumed `2022-04-12 01:03` — missing 3 hour(s)

## 3. Media objects file size histogram

![Jeen Yuhs collection size histogram](figures/jeen-yuhs-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/jeen-yuhs-01-downloads-by-week-jeen-yuhs-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![jeen-yuhs-01 downloads by day](figures/jeen-yuhs-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 12.13 | 18.24 | 15.35 | 47.14 | 1.11 | 1.00 |

### Cumulative network infrastructure

[![Jeen Yuhs cumulative map](figures/jeen-yuhs-01-carto.png)](figures/jeen-yuhs-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/jeen-yuhs-01-data-ge-1080p.webp)](figures/jeen-yuhs-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/jeen-yuhs-01-data-lt-1080p.webp)](figures/jeen-yuhs-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
