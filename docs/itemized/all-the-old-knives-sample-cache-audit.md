---
layout: default
title: "all-the-old-knives Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# all-the-old-knives sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | All The Old Knives |
| Collection key | `all-the-old-knives` |
| imdb_id | [tt3706352](https://www.imdb.com/title/tt3706352/) |
| wikipedia_url | [All the Old Knives](https://en.wikipedia.org/wiki/All_the_Old_Knives) |
| Sample dates | 2022-04-08-to-2022-06-23 |
| Sample days | 77 |
| BTIH count | 122 |
| Unique BTIH count | 96 |
| Downloaders total | 4,517,730 |
| Uploaders total | 1,760,978 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:10Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/all-the-old-knives.xz`
- Hour directories: 1830
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![All The Old Knives collection size histogram](figures/all-the-old-knives-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/all-the-old-knives-downloads-by-week-all-the-old-knives-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![all-the-old-knives downloads by day](figures/all-the-old-knives-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 18.06 | 12.62 | 22.50 | 36.01 | 2.47 | 0.55 |

### Cumulative network infrastructure

[![All The Old Knives cumulative map](figures/all-the-old-knives-carto.png)](figures/all-the-old-knives-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/all-the-old-knives-data-ge-1080p.webp)](figures/all-the-old-knives-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/all-the-old-knives-data-lt-1080p.webp)](figures/all-the-old-knives-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
