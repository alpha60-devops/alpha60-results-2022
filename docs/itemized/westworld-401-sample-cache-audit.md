---
layout: default
title: "westworld-401 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# westworld-401 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Westworld |
| Collection key | `westworld-401` |
| imdb_id | [tt0475784](https://www.imdb.com/title/tt0475784/) |
| wikipedia_url | [Westworld (TV series)](https://en.wikipedia.org/wiki/Westworld_(TV_series)) |
| Sample dates | 2022-06-27-to-2022-09-04 |
| Sample days | 70 |
| BTIH count | 119 |
| Unique BTIH count | 102 |
| Downloaders total | 2,404,570 |
| Uploaders total | 648,032 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:22Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/westworld-401.xz`
- Hour directories: 1673
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Westworld collection size histogram](figures/westworld-401-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/westworld-401-downloads-by-week-westworld-401-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![westworld-401 downloads by day](figures/westworld-401-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/westworld-401-cumulative-aggregate.geojson.gz" data-map-title="Westworld — westworld-401" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Westworld (westworld-401) cumulative data map in new window" title="Opens interactive map for Westworld (westworld-401) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.26 | 19.36 | 24.62 | 40.59 | 3.32 | 0.68 |

### Network infrastructure

[![Westworld cumulative map](figures/westworld-401-carto.png)](figures/westworld-401-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/westworld-401-data-ge-1080p.webp)](figures/westworld-401-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/westworld-401-data-lt-1080p.webp)](figures/westworld-401-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
