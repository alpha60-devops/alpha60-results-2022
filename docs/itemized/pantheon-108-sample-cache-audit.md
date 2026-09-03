---
layout: default
title: "pantheon-108 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# pantheon-108 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Pantheon |
| Collection key | `pantheon-108` |
| imdb_id | [tt11680642](https://www.imdb.com/title/tt11680642/) |
| wikipedia_url | [Pantheon (TV series)](https://en.wikipedia.org/wiki/Pantheon_(TV_series)) |
| Sample dates | 2022-10-13-to-2022-12-20 |
| Sample days | 69 |
| BTIH count | 69 |
| Unique BTIH count | 56 |
| Downloaders total | 597,695 |
| Uploaders total | 70,787 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:17Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/pantheon-108.xz`
- Hour directories: 1638
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Pantheon collection size histogram](figures/pantheon-108-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/pantheon-108-downloads-by-week-pantheon-108-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![pantheon-108 downloads by day](figures/pantheon-108-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.19 | 14.82 | 23.46 | 42.65 | 1.54 | 5.12 |

### Cumulative network infrastructure

[![Pantheon cumulative map](figures/pantheon-108-carto.png)](figures/pantheon-108-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/pantheon-108-data-ge-1080p.webp)](figures/pantheon-108-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/pantheon-108-data-lt-1080p.webp)](figures/pantheon-108-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
