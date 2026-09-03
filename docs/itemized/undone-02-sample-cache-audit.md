---
layout: default
title: "undone-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# undone-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Undone |
| Collection key | `undone-02` |
| imdb_id | [tt8101850](https://www.imdb.com/title/tt8101850/) |
| wikipedia_url | [Undone (TV series)](https://en.wikipedia.org/wiki/Undone_(TV_series)) |
| Sample dates | 2022-04-29-to-2022-08-11 |
| Sample days | 105 |
| BTIH count | 198 |
| Unique BTIH count | 168 |
| Downloaders total | 2,256,627 |
| Uploaders total | 262,536 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:21Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/undone-02.xz`
- Hour directories: 2504
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Undone collection size histogram](figures/undone-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/undone-02-downloads-by-week-undone-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![undone-02 downloads by day](figures/undone-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.44 | 19.79 | 18.42 | 54.59 | 1.24 | 1.14 |

### Cumulative network infrastructure

[![Undone cumulative map](figures/undone-02-carto.png)](figures/undone-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/undone-02-data-ge-1080p.webp)](figures/undone-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/undone-02-data-lt-1080p.webp)](figures/undone-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
