---
layout: default
title: "undone-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# undone-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Undone |
| Collection key | `undone-02` |
| imdb_id | [tt8101850](https://www.imdb.com/title/tt8101850/) |
| wikipedia_url | [Undone (TV series)](https://en.wikipedia.org/wiki/Undone_(TV_series)) |
| Sample dates | 2022-04-29-to-2022-08-11 |
| Sample days | 105 |
| BTIH count | 198 |
| Unique BTIH count | 168 |
| Downloaders total | 2,256,627 |
| Uploaders total | 262,536 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:21Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/undone-02.xz`
- Hour directories: 2504
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Undone collection size histogram](figures/undone-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/undone-02-downloads-by-week-undone-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![undone-02 downloads by day](figures/undone-02-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/undone-02-cumulative-aggregate.geojson.gz" data-map-title="Undone — undone-02" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Undone (undone-02) cumulative data map in new window" title="Opens interactive map for Undone (undone-02) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.44 | 19.79 | 18.42 | 54.59 | 1.24 | 1.14 |

### Network infrastructure

[![Undone cumulative map](figures/undone-02-carto.png)](figures/undone-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/undone-02-data-ge-1080p.webp)](figures/undone-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/undone-02-data-lt-1080p.webp)](figures/undone-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
