---
layout: default
title: "yellowstone-505 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# yellowstone-505 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Yellowstone |
| Collection key | `yellowstone-505` |
| imdb_id | [tt4236770](https://www.imdb.com/title/tt4236770/) |
| wikipedia_url | [Yellowstone (TV series)](https://en.wikipedia.org/wiki/Yellowstone_(TV_series)) |
| Sample dates | 2022-12-05-to-2022-12-08 |
| Sample days | 4 |
| BTIH count | 53 |
| Unique BTIH count | 45 |
| Downloaders total | 265,228 |
| Uploaders total | 87,115 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-09T22:54:33Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/yellowstone-505.xz`
- Hour directories: 92
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Yellowstone collection size histogram](figures/yellowstone-505-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/yellowstone-505-downloads-by-week-yellowstone-505-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![yellowstone-505 downloads by day](figures/yellowstone-505-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/yellowstone-505-cumulative-aggregate.geojson.gz" data-map-title="Yellowstone — yellowstone-505" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Yellowstone (yellowstone-505) cumulative data map in new window" title="Opens interactive map for Yellowstone (yellowstone-505) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.92 | 31.27 | 10.93 | 25.66 | 6.56 | 0.31 |

### Network infrastructure

[![Yellowstone cumulative map](figures/yellowstone-505-carto.png)](figures/yellowstone-505-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/yellowstone-505-data-ge-1080p.webp)](figures/yellowstone-505-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/yellowstone-505-data-lt-1080p.webp)](figures/yellowstone-505-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
