---
layout: default
title: "andy-warhol-diaries-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# andy-warhol-diaries-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Andy Warhol Diaries |
| Collection key | `andy-warhol-diaries-01` |
| imdb_id | [tt18082212](https://www.imdb.com/title/tt18082212/) |
| wikipedia_url | [The Andy Warhol Diaries (TV series)](https://en.wikipedia.org/wiki/The_Andy_Warhol_Diaries_(TV_series)) |
| Sample dates | 2022-03-09-to-2022-05-17 |
| Sample days | 70 |
| BTIH count | 50 |
| Unique BTIH count | 37 |
| Downloaders total | 457,126 |
| Uploaders total | 64,671 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:11Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/andy-warhol-diaries-01.xz`
- Hour directories: 1661
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (1 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-03-27 01:06`, resumed `2022-03-27 03:06` — missing 1 hour(s)

## 3. File sizes histogram *median[lowest, highest]*

![The Andy Warhol Diaries collection size histogram](figures/andy-warhol-diaries-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/andy-warhol-diaries-01-downloads-by-week-andy-warhol-diaries-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![andy-warhol-diaries-01 downloads by day](figures/andy-warhol-diaries-01-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/andy-warhol-diaries-01-cumulative-aggregate.geojson.gz" data-map-title="The Andy Warhol Diaries — andy-warhol-diaries-01" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Andy Warhol Diaries (andy-warhol-diaries-01) cumulative data map in new window" title="Opens interactive map for The Andy Warhol Diaries (andy-warhol-diaries-01) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.65 | 15.81 | 16.26 | 55.95 | 1.12 | 1.17 |

### Network infrastructure

[![The Andy Warhol Diaries cumulative map](figures/andy-warhol-diaries-01-carto.png)](figures/andy-warhol-diaries-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/andy-warhol-diaries-01-data-ge-1080p.webp)](figures/andy-warhol-diaries-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/andy-warhol-diaries-01-data-lt-1080p.webp)](figures/andy-warhol-diaries-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
