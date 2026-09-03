---
layout: default
title: "renaissance Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# renaissance sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | RENAISSANCE |
| Collection key | `renaissance` |
| imdb_id | [tt0386741](https://www.imdb.com/title/tt0386741/) |
| wikipedia_url | [Renaissance (2006 film)](https://en.wikipedia.org/wiki/Renaissance_(2006_film)) |
| Sample dates | 2022-07-29-to-2022-10-06 |
| Sample days | 70 |
| BTIH count | 24 |
| Unique BTIH count | 19 |
| Downloaders total | 268,114 |
| Uploaders total | 49,964 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:19Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/renaissance.xz`
- Hour directories: 1661
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![RENAISSANCE collection size histogram](figures/renaissance-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/renaissance-downloads-by-week-renaissance-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![renaissance downloads by day](figures/renaissance-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 8.22 | 15.81 | 13.50 | 37.24 | 1.26 | 0.57 |

### Cumulative network infrastructure

[![RENAISSANCE cumulative map](figures/renaissance-carto.png)](figures/renaissance-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

UNAVAILABLE — no collection members at 1080p or 2160 resolution.

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/renaissance-data-lt-1080p.webp)](figures/renaissance-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
