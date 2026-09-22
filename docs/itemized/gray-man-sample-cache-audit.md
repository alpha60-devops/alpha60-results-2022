---
layout: default
title: "gray-man Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# gray-man sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Gray Man |
| Collection key | `gray-man` |
| imdb_id | [tt1649418](https://www.imdb.com/title/tt1649418/) |
| wikipedia_url | [The Gray Man (2022 film)](https://en.wikipedia.org/wiki/The_Gray_Man_(2022_film)) |
| Sample dates | 2022-07-22-to-2022-11-03 |
| Sample days | 105 |
| BTIH count | 249 |
| Unique BTIH count | 223 |
| Downloaders total | 11,050,555 |
| Uploaders total | 3,919,358 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:15Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/gray-man.xz`
- Hour directories: 2502
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![The Gray Man collection size histogram](figures/gray-man-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/gray-man-downloads-by-week-gray-man-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![gray-man downloads by day](figures/gray-man-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/gray-man-cumulative-aggregate.geojson.gz" data-map-title="The Gray Man — gray-man" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Gray Man (gray-man) cumulative data map in new window" title="Opens interactive map for The Gray Man (gray-man) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 11.45 | 11.21 | 30.99 | 37.39 | 1.59 | 0.57 |

### Network infrastructure

[![The Gray Man cumulative map](figures/gray-man-carto.png)](figures/gray-man-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/gray-man-data-ge-1080p.webp)](figures/gray-man-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/gray-man-data-lt-1080p.webp)](figures/gray-man-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
