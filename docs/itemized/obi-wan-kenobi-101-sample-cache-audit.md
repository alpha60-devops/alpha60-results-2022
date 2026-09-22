---
layout: default
title: "obi-wan-kenobi-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# obi-wan-kenobi-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Obi-Wan Kenobi |
| Collection key | `obi-wan-kenobi-101` |
| imdb_id | [tt8466564](https://www.imdb.com/title/tt8466564/) |
| wikipedia_url | [Obi-Wan Kenobi (miniseries)](https://en.wikipedia.org/wiki/Obi-Wan_Kenobi_(miniseries)) |
| Sample dates | 2022-05-27-to-2022-09-29 |
| Sample days | 126 |
| BTIH count | 365 |
| Unique BTIH count | 321 |
| Downloaders total | 14,562,800 |
| Uploaders total | 5,025,955 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:16Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/obi-wan-kenobi-101.xz`
- Hour directories: 3017
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Obi-Wan Kenobi collection size histogram](figures/obi-wan-kenobi-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/obi-wan-kenobi-101-downloads-by-week-obi-wan-kenobi-101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![obi-wan-kenobi-101 downloads by day](figures/obi-wan-kenobi-101-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/obi-wan-kenobi-101-cumulative-aggregate.geojson.gz" data-map-title="Obi-Wan Kenobi — obi-wan-kenobi-101" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Obi-Wan Kenobi (obi-wan-kenobi-101) cumulative data map in new window" title="Opens interactive map for Obi-Wan Kenobi (obi-wan-kenobi-101) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.32 | 22.31 | 18.76 | 45.92 | 3.38 | 0.58 |

### Network infrastructure

[![Obi-Wan Kenobi cumulative map](figures/obi-wan-kenobi-101-carto.png)](figures/obi-wan-kenobi-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/obi-wan-kenobi-101-data-ge-1080p.webp)](figures/obi-wan-kenobi-101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/obi-wan-kenobi-101-data-lt-1080p.webp)](figures/obi-wan-kenobi-101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
