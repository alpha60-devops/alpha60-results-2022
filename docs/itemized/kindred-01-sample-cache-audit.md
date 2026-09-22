---
layout: default
title: "kindred-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# kindred-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Kindred |
| Collection key | `kindred-01` |
| imdb_id | [tt14376190](https://www.imdb.com/title/tt14376190/) |
| wikipedia_url | [Kindred (TV series)](https://en.wikipedia.org/wiki/Kindred_(TV_series)) |
| Sample dates | 2022-12-13-to-2023-02-20 |
| Sample days | 70 |
| BTIH count | 192 |
| Unique BTIH count | 183 |
| Downloaders total | 1,121,443 |
| Uploaders total | 112,237 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-09T22:54:29Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/kindred-01.xz`
- Hour directories: 1662
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Kindred collection size histogram](figures/kindred-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/kindred-01-downloads-by-week-kindred-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![kindred-01 downloads by day](figures/kindred-01-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/kindred-01-cumulative-aggregate.geojson.gz" data-map-title="Kindred — kindred-01" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Kindred (kindred-01) cumulative data map in new window" title="Opens interactive map for Kindred (kindred-01) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.54 | 21.37 | 18.00 | 52.36 | 1.37 | 0.97 |

### Network infrastructure

[![Kindred cumulative map](figures/kindred-01-carto.png)](figures/kindred-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/kindred-01-data-ge-1080p.webp)](figures/kindred-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/kindred-01-data-lt-1080p.webp)](figures/kindred-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
