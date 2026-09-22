---
layout: default
title: "all-the-old-knives Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# all-the-old-knives sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | All The Old Knives |
| Collection key | `all-the-old-knives` |
| imdb_id | [tt3706352](https://www.imdb.com/title/tt3706352/) |
| wikipedia_url | [All the Old Knives](https://en.wikipedia.org/wiki/All_the_Old_Knives) |
| Sample dates | 2022-04-08-to-2022-06-23 |
| Sample days | 77 |
| BTIH count | 122 |
| Unique BTIH count | 96 |
| Downloaders total | 4,517,730 |
| Uploaders total | 1,760,978 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:10Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/all-the-old-knives.xz`
- Hour directories: 1830
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![All The Old Knives collection size histogram](figures/all-the-old-knives-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/all-the-old-knives-downloads-by-week-all-the-old-knives-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![all-the-old-knives downloads by day](figures/all-the-old-knives-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/all-the-old-knives-cumulative-aggregate.geojson.gz" data-map-title="All The Old Knives — all-the-old-knives" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open All The Old Knives (all-the-old-knives) cumulative data map in new window" title="Opens interactive map for All The Old Knives (all-the-old-knives) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 18.06 | 12.62 | 22.50 | 36.01 | 2.47 | 0.55 |

### Network infrastructure

[![All The Old Knives cumulative map](figures/all-the-old-knives-carto.png)](figures/all-the-old-knives-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/all-the-old-knives-data-ge-1080p.webp)](figures/all-the-old-knives-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/all-the-old-knives-data-lt-1080p.webp)](figures/all-the-old-knives-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
