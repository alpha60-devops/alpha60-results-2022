---
layout: default
title: "atlanta-301 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# atlanta-301 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Atlanta |
| Collection key | `atlanta-301` |
| imdb_id | [tt4288182](https://www.imdb.com/title/tt4288182/) |
| wikipedia_url | [Atlanta (TV series)](https://en.wikipedia.org/wiki/Atlanta_(TV_series)) |
| Sample dates | 2022-03-25-to-2022-06-02 |
| Sample days | 70 |
| BTIH count | 90 |
| Unique BTIH count | 76 |
| Downloaders total | 1,199,444 |
| Uploaders total | 287,118 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:11Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/atlanta-301.xz`
- Hour directories: 1665
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (1 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-03-27 01:03`, resumed `2022-03-27 03:03` — missing 1 hour(s)

## 3. File sizes histogram *median[lowest, highest]*

![Atlanta collection size histogram](figures/atlanta-301-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/atlanta-301-downloads-by-week-atlanta-301-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![atlanta-301 downloads by day](figures/atlanta-301-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/atlanta-301-cumulative-aggregate.geojson.gz" data-map-title="Atlanta — atlanta-301" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Atlanta (atlanta-301) cumulative data map in new window" title="Opens interactive map for Atlanta (atlanta-301) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 11.26 | 28.01 | 11.92 | 38.42 | 2.66 | 0.60 |

### Network infrastructure

[![Atlanta cumulative map](figures/atlanta-301-carto.png)](figures/atlanta-301-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/atlanta-301-data-ge-1080p.webp)](figures/atlanta-301-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/atlanta-301-data-lt-1080p.webp)](figures/atlanta-301-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
