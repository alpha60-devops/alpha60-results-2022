---
layout: default
title: "stranger-things-04.1 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# stranger-things-04.1 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Stranger Things |
| Collection key | `stranger-things-04.1` |
| imdb_id | [tt4574334](https://www.imdb.com/title/tt4574334/) |
| wikipedia_url | [Stranger Things](https://en.wikipedia.org/wiki/Stranger_Things) |
| Sample dates | 2022-05-27-to-2022-09-29 |
| Sample days | 126 |
| BTIH count | 421 |
| Unique BTIH count | 396 |
| Downloaders total | 15,433,990 |
| Uploaders total | 6,755,377 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:21Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/stranger-things-04.1.xz`
- Hour directories: 3005
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (2 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-05-27 22:00`, resumed `2022-05-28 01:00` — missing 2 hour(s)

## 3. Media objects file size histogram

![Stranger Things collection size histogram](figures/stranger-things-04.1-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/stranger-things-04-1-downloads-by-week-stranger-things-04.1-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![stranger-things-04.1 downloads by day](figures/stranger-things-04-1-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 7.43 | 17.61 | 27.19 | 42.65 | 2.14 | 0.57 |

### Cumulative network infrastructure

[![Stranger Things cumulative map](figures/stranger-things-04.1-carto.png)](figures/stranger-things-04.1-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/stranger-things-04.1-data-ge-1080p.webp)](figures/stranger-things-04.1-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/stranger-things-04.1-data-lt-1080p.webp)](figures/stranger-things-04.1-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
