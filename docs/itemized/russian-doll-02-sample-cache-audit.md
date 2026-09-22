---
layout: default
title: "russian-doll-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# russian-doll-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Russian Doll |
| Collection key | `russian-doll-02` |
| imdb_id | [tt7520794](https://www.imdb.com/title/tt7520794/) |
| wikipedia_url | [Russian Doll (TV series)](https://en.wikipedia.org/wiki/Russian_Doll_(TV_series)) |
| Sample dates | 2022-04-20-to-2022-06-28 |
| Sample days | 70 |
| BTIH count | 166 |
| Unique BTIH count | 150 |
| Downloaders total | 1,626,866 |
| Uploaders total | 349,651 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:20Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/russian-doll-02.xz`
- Hour directories: 1662
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Russian Doll collection size histogram](figures/russian-doll-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/russian-doll-02-downloads-by-week-russian-doll-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![russian-doll-02 downloads by day](figures/russian-doll-02-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/russian-doll-02-cumulative-aggregate.geojson.gz" data-map-title="Russian Doll — russian-doll-02" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Russian Doll (russian-doll-02) cumulative data map in new window" title="Opens interactive map for Russian Doll (russian-doll-02) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.40 | 20.41 | 16.43 | 51.13 | 2.27 | 0.94 |

### Network infrastructure

[![Russian Doll cumulative map](figures/russian-doll-02-carto.png)](figures/russian-doll-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/russian-doll-02-data-ge-1080p.webp)](figures/russian-doll-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/russian-doll-02-data-lt-1080p.webp)](figures/russian-doll-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
