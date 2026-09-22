---
layout: default
title: "peripheral-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# peripheral-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Peripheral |
| Collection key | `peripheral-101` |
| imdb_id | [tt8291284](https://www.imdb.com/title/tt8291284/) |
| wikipedia_url | [The Peripheral (TV series)](https://en.wikipedia.org/wiki/The_Peripheral_(TV_series)) |
| Sample dates | 2022-10-21-to-2023-02-16 |
| Sample days | 119 |
| BTIH count | 188 |
| Unique BTIH count | 157 |
| Downloaders total | 6,073,770 |
| Uploaders total | 1,855,439 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:18Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/peripheral-101.xz`
- Hour directories: 2853
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![The Peripheral collection size histogram](figures/peripheral-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/peripheral-101-downloads-by-week-peripheral-101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![peripheral-101 downloads by day](figures/peripheral-101-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/peripheral-101-cumulative-aggregate.geojson.gz" data-map-title="The Peripheral — peripheral-101" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Peripheral (peripheral-101) cumulative data map in new window" title="Opens interactive map for The Peripheral (peripheral-101) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.24 | 16.03 | 26.31 | 43.46 | 2.88 | 1.21 |

### Network infrastructure

[![The Peripheral cumulative map](figures/peripheral-101-carto.png)](figures/peripheral-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/peripheral-101-data-ge-1080p.webp)](figures/peripheral-101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/peripheral-101-data-lt-1080p.webp)](figures/peripheral-101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
