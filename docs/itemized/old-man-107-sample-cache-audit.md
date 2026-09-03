---
layout: default
title: "old-man-107 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# old-man-107 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Old Man |
| Collection key | `old-man-107` |
| imdb_id | [tt5645432](https://www.imdb.com/title/tt5645432/) |
| wikipedia_url | [The Old Man (TV series)](https://en.wikipedia.org/wiki/The_Old_Man_(TV_series)) |
| Sample dates | 2022-07-23-to-2022-09-30 |
| Sample days | 70 |
| BTIH count | 139 |
| Unique BTIH count | 123 |
| Downloaders total | 2,139,560 |
| Uploaders total | 579,174 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:17Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/old-man-107.xz`
- Hour directories: 1679
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (1 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-08-05 22:03`, resumed `2022-08-06 00:03` — missing 1 hour(s)

## 3. Media objects file size histogram

![The Old Man collection size histogram](figures/old-man-107-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/old-man-107-downloads-by-week-old-man-107-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![old-man-107 downloads by day](figures/old-man-107-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.59 | 18.73 | 17.34 | 50.10 | 3.03 | 0.78 |

### Cumulative network infrastructure

[![The Old Man cumulative map](figures/old-man-107-carto.png)](figures/old-man-107-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/old-man-107-data-ge-1080p.webp)](figures/old-man-107-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/old-man-107-data-lt-1080p.webp)](figures/old-man-107-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
