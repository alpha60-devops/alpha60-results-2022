---
layout: default
title: "atlanta-310 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# atlanta-310 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Atlanta |
| Collection key | `atlanta-310` |
| imdb_id | [tt4288182](https://www.imdb.com/title/tt4288182/) |
| wikipedia_url | [Atlanta (TV series)](https://en.wikipedia.org/wiki/Atlanta_(TV_series)) |
| Sample dates | 2022-05-20-to-2022-07-28 |
| Sample days | 70 |
| BTIH count | 62 |
| Unique BTIH count | 54 |
| Downloaders total | 600,689 |
| Uploaders total | 134,102 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:12Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/atlanta-310.xz`
- Hour directories: 1670
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (2 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-05-27 22:03`, resumed `2022-05-28 01:03` — missing 2 hour(s)

## 3. File sizes histogram *median[lowest, highest]*

![Atlanta collection size histogram](figures/atlanta-310-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/atlanta-310-downloads-by-week-atlanta-310-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![atlanta-310 downloads by day](figures/atlanta-310-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/atlanta-310-cumulative-aggregate.geojson.gz" data-map-title="Atlanta — atlanta-310" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Atlanta (atlanta-310) cumulative data map in new window" title="Opens interactive map for Atlanta (atlanta-310) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.25 | 24.08 | 15.15 | 45.36 | 2.01 | 0.82 |

### Network infrastructure

[![Atlanta cumulative map](figures/atlanta-310-carto.png)](figures/atlanta-310-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/atlanta-310-data-ge-1080p.webp)](figures/atlanta-310-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/atlanta-310-data-lt-1080p.webp)](figures/atlanta-310-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
