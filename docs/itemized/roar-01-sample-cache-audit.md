---
layout: default
title: "roar-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# roar-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Roar |
| Collection key | `roar-01` |
| imdb_id | [tt9174600](https://www.imdb.com/title/tt9174600/) |
| wikipedia_url | [Roar (2022 TV series)](https://en.wikipedia.org/wiki/Roar_(2022_TV_series)) |
| Sample dates | 2022-04-15-to-2022-06-23 |
| Sample days | 70 |
| BTIH count | 166 |
| Unique BTIH count | 146 |
| Downloaders total | 1,305,384 |
| Uploaders total | 214,977 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:20Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/roar-01.xz`
- Hour directories: 1658
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (2 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-05-27 22:06`, resumed `2022-05-28 01:06` — missing 2 hour(s)

## 3. Media objects file size histogram

![Roar collection size histogram](figures/roar-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/roar-01-downloads-by-week-roar-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![roar-01 downloads by day](figures/roar-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.66 | 19.47 | 17.78 | 53.46 | 1.50 | 1.09 |

### Cumulative network infrastructure

[![Roar cumulative map](figures/roar-01-carto.png)](figures/roar-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/roar-01-data-ge-1080p.webp)](figures/roar-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/roar-01-data-lt-1080p.webp)](figures/roar-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
