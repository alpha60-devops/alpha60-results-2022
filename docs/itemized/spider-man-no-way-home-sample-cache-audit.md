---
layout: default
title: "spider-man-no-way-home Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# spider-man-no-way-home sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Spider Man No Way Home |
| Collection key | `spider-man-no-way-home` |
| imdb_id | [tt10872600](https://www.imdb.com/title/tt10872600/) |
| wikipedia_url | [Spider-Man: No Way Home](https://en.wikipedia.org/wiki/Spider-Man:_No_Way_Home) |
| Sample dates | 2022-03-11-to-2022-09-08 |
| Sample days | 182 |
| BTIH count | 560 |
| Unique BTIH count | 484 |
| Downloaders total | 40,404,189 |
| Uploaders total | 14,260,252 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:20Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/spider-man-no-way-home.xz`
- Hour directories: 4347
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Spider Man No Way Home collection size histogram](figures/spider-man-no-way-home-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/spider-man-no-way-home-downloads-by-week-spider-man-no-way-home-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![spider-man-no-way-home downloads by day](figures/spider-man-no-way-home-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/spider-man-no-way-home-cumulative-aggregate.geojson.gz" data-map-title="Spider Man No Way Home — spider-man-no-way-home" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Spider Man No Way Home (spider-man-no-way-home) cumulative data map in new window" title="Opens interactive map for Spider Man No Way Home (spider-man-no-way-home) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 7.24 | 15.60 | 31.95 | 35.23 | 1.76 | 0.70 |

### Network infrastructure

[![Spider Man No Way Home cumulative map](figures/spider-man-no-way-home-carto.png)](figures/spider-man-no-way-home-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/spider-man-no-way-home-data-ge-1080p.webp)](figures/spider-man-no-way-home-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/spider-man-no-way-home-data-lt-1080p.webp)](figures/spider-man-no-way-home-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
