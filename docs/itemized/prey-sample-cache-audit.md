---
layout: default
title: "prey Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# prey sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Prey |
| Collection key | `prey` |
| imdb_id | [tt11866324](https://www.imdb.com/title/tt11866324/) |
| wikipedia_url | [Prey (2022 film)](https://en.wikipedia.org/wiki/Prey_(2022_film)) |
| Sample dates | 2022-08-05-to-2023-02-02 |
| Sample days | 182 |
| BTIH count | 320 |
| Unique BTIH count | 261 |
| Downloaders total | 24,539,733 |
| Uploaders total | 9,951,981 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:18Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/prey.xz`
- Hour directories: 4349
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Prey collection size histogram](figures/prey-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/prey-downloads-by-week-prey-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![prey downloads by day](figures/prey-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 7.16 | 12.51 | 25.58 | 47.88 | 1.66 | 0.61 |

### Cumulative network infrastructure

[![Prey cumulative map](figures/prey-carto.png)](figures/prey-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/prey-data-ge-1080p.webp)](figures/prey-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/prey-data-lt-1080p.webp)](figures/prey-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
