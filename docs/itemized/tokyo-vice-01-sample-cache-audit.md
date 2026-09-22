---
layout: default
title: "tokyo-vice-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# tokyo-vice-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Tokyo Vice |
| Collection key | `tokyo-vice-01` |
| imdb_id | [tt2887954](https://www.imdb.com/title/tt2887954/) |
| wikipedia_url | [Tokyo Vice (TV series)](https://en.wikipedia.org/wiki/Tokyo_Vice_(TV_series)) |
| Sample dates | 2022-04-07-to-2022-07-20 |
| Sample days | 105 |
| BTIH count | 269 |
| Unique BTIH count | 226 |
| Downloaders total | 4,842,874 |
| Uploaders total | 1,438,804 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-09T22:54:32Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/tokyo-vice-01.xz`
- Hour directories: 2503
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Tokyo Vice collection size histogram](figures/tokyo-vice-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/tokyo-vice-01-downloads-by-week-tokyo-vice-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![tokyo-vice-01 downloads by day](figures/tokyo-vice-01-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/tokyo-vice-01-cumulative-aggregate.geojson.gz" data-map-title="Tokyo Vice — tokyo-vice-01" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Tokyo Vice (tokyo-vice-01) cumulative data map in new window" title="Opens interactive map for Tokyo Vice (tokyo-vice-01) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.36 | 18.19 | 20.13 | 49.34 | 2.44 | 1.03 |

### Network infrastructure

[![Tokyo Vice cumulative map](figures/tokyo-vice-01-carto.png)](figures/tokyo-vice-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/tokyo-vice-01-data-ge-1080p.webp)](figures/tokyo-vice-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/tokyo-vice-01-data-lt-1080p.webp)](figures/tokyo-vice-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
