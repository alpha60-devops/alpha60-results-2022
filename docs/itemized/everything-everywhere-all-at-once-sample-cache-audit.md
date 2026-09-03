---
layout: default
title: "everything-everywhere-all-at-once Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# everything-everywhere-all-at-once sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Everything Everywhere All At Once |
| Collection key | `everything-everywhere-all-at-once` |
| imdb_id | [tt6710474](https://www.imdb.com/title/tt6710474/) |
| wikipedia_url | [Everything Everywhere All at Once](https://en.wikipedia.org/wiki/Everything_Everywhere_All_at_Once) |
| Sample dates | 2022-05-19-to-2022-08-31 |
| Sample days | 105 |
| BTIH count | 250 |
| Unique BTIH count | 212 |
| Downloaders total | 13,249,300 |
| Uploaders total | 4,852,593 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:13Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/everything-everywhere-all-at-once.xz`
- Hour directories: 2514
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Everything Everywhere All At Once collection size histogram](figures/everything-everywhere-all-at-once-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/everything-everywhere-all-at-once-downloads-by-week-everything-everywhere-all-at-once-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![everything-everywhere-all-at-once downloads by day](figures/everything-everywhere-all-at-once-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.32 | 18.49 | 24.93 | 36.81 | 2.13 | 0.65 |

### Cumulative network infrastructure

[![Everything Everywhere All At Once cumulative map](figures/everything-everywhere-all-at-once-carto.png)](figures/everything-everywhere-all-at-once-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/everything-everywhere-all-at-once-data-ge-1080p.webp)](figures/everything-everywhere-all-at-once-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/everything-everywhere-all-at-once-data-lt-1080p.webp)](figures/everything-everywhere-all-at-once-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
