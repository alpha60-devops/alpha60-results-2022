---
layout: default
title: "boys-301 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# boys-301 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Boys |
| Collection key | `boys-301` |
| imdb_id | [tt1190634](https://www.imdb.com/title/tt1190634/) |
| wikipedia_url | [The Boys (TV series)](https://en.wikipedia.org/wiki/The_Boys_(TV_series)) |
| Sample dates | 2022-06-03-to-2022-09-22 |
| Sample days | 112 |
| BTIH count | 318 |
| Unique BTIH count | 273 |
| Downloaders total | 15,936,745 |
| Uploaders total | 5,539,530 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:12Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/boys-301.xz`
- Hour directories: 2664
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (21 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-08-06 23:00`, resumed `2022-08-07 21:00` — missing 21 hour(s)

## 3. File sizes histogram *median[lowest, highest]*

![The Boys collection size histogram](figures/boys-301-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/boys-301-downloads-by-week-boys-301-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![boys-301 downloads by day](figures/boys-301-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/boys-301-cumulative-aggregate.geojson.gz" data-map-title="The Boys — boys-301" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Boys (boys-301) cumulative data map in new window" title="Opens interactive map for The Boys (boys-301) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 7.28 | 21.13 | 29.12 | 34.91 | 3.53 | 0.60 |

### Network infrastructure

[![The Boys cumulative map](figures/boys-301-carto.png)](figures/boys-301-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/boys-301-data-ge-1080p.webp)](figures/boys-301-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/boys-301-data-lt-1080p.webp)](figures/boys-301-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
