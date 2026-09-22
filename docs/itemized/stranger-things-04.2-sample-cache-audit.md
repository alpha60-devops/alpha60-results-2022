---
layout: default
title: "stranger-things-04.2 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# stranger-things-04.2 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Stranger Things |
| Collection key | `stranger-things-04.2` |
| imdb_id | [tt4574334](https://www.imdb.com/title/tt4574334/) |
| wikipedia_url | [Stranger Things](https://en.wikipedia.org/wiki/Stranger_Things) |
| Sample dates | 2022-07-01-to-2022-10-13 |
| Sample days | 105 |
| BTIH count | 264 |
| Unique BTIH count | 234 |
| Downloaders total | 9,301,199 |
| Uploaders total | 3,427,872 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:21Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/stranger-things-04.2.xz`
- Hour directories: 2511
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Stranger Things collection size histogram](figures/stranger-things-04.2-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/stranger-things-04-2-downloads-by-week-stranger-things-04.2-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![stranger-things-04.2 downloads by day](figures/stranger-things-04-2-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/stranger-things-04.2-cumulative-aggregate.geojson.gz" data-map-title="Stranger Things — stranger-things-04.2" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Stranger Things (stranger-things-04.2) cumulative data map in new window" title="Opens interactive map for Stranger Things (stranger-things-04.2) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.10 | 16.10 | 28.28 | 42.65 | 1.85 | 0.55 |

### Network infrastructure

[![Stranger Things cumulative map](figures/stranger-things-04.2-carto.png)](figures/stranger-things-04.2-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/stranger-things-04.2-data-ge-1080p.webp)](figures/stranger-things-04.2-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/stranger-things-04.2-data-lt-1080p.webp)](figures/stranger-things-04.2-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
