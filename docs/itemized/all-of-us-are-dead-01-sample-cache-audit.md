---
layout: default
title: "all-of-us-are-dead-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# all-of-us-are-dead-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | All of Us Are Dead |
| Collection key | `all-of-us-are-dead-01` |
| imdb_id | [tt14169960](https://www.imdb.com/title/tt14169960/) |
| wikipedia_url | [All of Us Are Dead](https://en.wikipedia.org/wiki/All_of_Us_Are_Dead) |
| Sample dates | 2022-01-28-to-2022-05-12 |
| Sample days | 105 |
| BTIH count | 230 |
| Unique BTIH count | 194 |
| Downloaders total | 6,486,828 |
| Uploaders total | 2,199,133 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:10Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/all-of-us-are-dead-01.xz`
- Hour directories: 2502
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (1 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-03-27 01:03`, resumed `2022-03-27 03:03` — missing 1 hour(s)

## 3. Media objects file size histogram

![All of Us Are Dead collection size histogram](figures/all-of-us-are-dead-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/all-of-us-are-dead-01-downloads-by-week-all-of-us-are-dead-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![all-of-us-are-dead-01 downloads by day](figures/all-of-us-are-dead-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.67 | 11.18 | 43.32 | 32.57 | 0.98 | 0.94 |

### Cumulative network infrastructure

[![All of Us Are Dead cumulative map](figures/all-of-us-are-dead-01-carto.png)](figures/all-of-us-are-dead-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/all-of-us-are-dead-01-data-ge-1080p.webp)](figures/all-of-us-are-dead-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/all-of-us-are-dead-01-data-lt-1080p.webp)](figures/all-of-us-are-dead-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
