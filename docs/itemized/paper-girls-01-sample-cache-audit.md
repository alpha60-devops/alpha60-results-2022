---
layout: default
title: "paper-girls-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# paper-girls-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Paper Girls |
| Collection key | `paper-girls-01` |
| imdb_id | [tt10623646](https://www.imdb.com/title/tt10623646/) |
| wikipedia_url | [Paper Girls (TV series)](https://en.wikipedia.org/wiki/Paper_Girls_(TV_series)) |
| Sample dates | 2022-07-29-to-2022-10-06 |
| Sample days | 70 |
| BTIH count | 217 |
| Unique BTIH count | 206 |
| Downloaders total | 1,424,612 |
| Uploaders total | 203,521 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:17Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/paper-girls-01.xz`
- Hour directories: 1661
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Paper Girls collection size histogram](figures/paper-girls-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/paper-girls-01-downloads-by-week-paper-girls-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![paper-girls-01 downloads by day](figures/paper-girls-01-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/paper-girls-01-cumulative-aggregate.geojson.gz" data-map-title="Paper Girls — paper-girls-01" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Paper Girls (paper-girls-01) cumulative data map in new window" title="Opens interactive map for Paper Girls (paper-girls-01) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.91 | 22.66 | 18.37 | 47.61 | 1.85 | 0.88 |

### Network infrastructure

[![Paper Girls cumulative map](figures/paper-girls-01-carto.png)](figures/paper-girls-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/paper-girls-01-data-ge-1080p.webp)](figures/paper-girls-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/paper-girls-01-data-lt-1080p.webp)](figures/paper-girls-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
