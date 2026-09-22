---
layout: default
title: "inventing-anna-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# inventing-anna-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Inventing Anna |
| Collection key | `inventing-anna-01` |
| imdb_id | [tt8740976](https://www.imdb.com/title/tt8740976/) |
| wikipedia_url | [Inventing Anna](https://en.wikipedia.org/wiki/Inventing_Anna) |
| Sample dates | 2022-02-11-to-2022-05-05 |
| Sample days | 84 |
| BTIH count | 238 |
| Unique BTIH count | 195 |
| Downloaders total | 3,504,172 |
| Uploaders total | 844,874 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-02T04:14:16Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/inventing-anna-01.xz`
- Hour directories: 1999
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (1 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2022-03-27 01:09`, resumed `2022-03-27 03:09` — missing 1 hour(s)

## 3. File sizes histogram *median[lowest, highest]*

![Inventing Anna collection size histogram](figures/inventing-anna-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/inventing-anna-01-downloads-by-week-inventing-anna-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![inventing-anna-01 downloads by day](figures/inventing-anna-01-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2022/refs/heads/main/data/geojson.cumulative/inventing-anna-01-cumulative-aggregate.geojson.gz" data-map-title="Inventing Anna — inventing-anna-01" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Inventing Anna (inventing-anna-01) cumulative data map in new window" title="Opens interactive map for Inventing Anna (inventing-anna-01) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 7.87 | 15.63 | 17.75 | 50.07 | 1.72 | 0.97 |

### Network infrastructure

[![Inventing Anna cumulative map](figures/inventing-anna-01-carto.png)](figures/inventing-anna-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/inventing-anna-01-data-ge-1080p.webp)](figures/inventing-anna-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/inventing-anna-01-data-lt-1080p.webp)](figures/inventing-anna-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
