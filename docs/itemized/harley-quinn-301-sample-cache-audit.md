---
layout: default
title: "harley-quinn-301 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# harley-quinn-301 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Harley Quinn |
| Collection key | `harley-quinn-301` |
| imdb_id | [tt7658402](https://www.imdb.com/title/tt7658402/) |
| wikipedia_url | [Harley Quinn (TV series)](https://en.wikipedia.org/wiki/Harley_Quinn_(TV_series)) |
| Sample dates | 2022-07-28-to-2022-10-05 |
| Sample days | 70 |
| BTIH count | 145 |
| Unique BTIH count | 119 |
| Downloaders total | 2,024,049 |
| Uploaders total | 393,298 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:15Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/harley-quinn-301.xz`
- Hour directories: 1655
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 2 (2 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-09-10 22:03`, resumed `2022-09-11 00:06` — missing 1 hour(s)
- hourly gap: last `2022-09-11 22:06`, resumed `2022-09-12 00:40` — missing 1 hour(s)

## 3. Media objects file size histogram

![Harley Quinn collection size histogram](figures/harley-quinn-301-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/harley-quinn-301-downloads-by-week-harley-quinn-301-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![harley-quinn-301 downloads by day](figures/harley-quinn-301-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.72 | 23.44 | 18.34 | 47.57 | 3.25 | 0.72 |

### Cumulative network infrastructure

[![Harley Quinn cumulative map](figures/harley-quinn-301-carto.png)](figures/harley-quinn-301-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/harley-quinn-301-data-ge-1080p.webp)](figures/harley-quinn-301-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/harley-quinn-301-data-lt-1080p.webp)](figures/harley-quinn-301-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
