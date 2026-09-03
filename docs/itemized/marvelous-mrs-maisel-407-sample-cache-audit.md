---
layout: default
title: "marvelous-mrs-maisel-407 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# marvelous-mrs-maisel-407 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Marvelous Mrs. Maisel |
| Collection key | `marvelous-mrs-maisel-407` |
| imdb_id | [tt5788792](https://www.imdb.com/title/tt5788792/) |
| wikipedia_url | [The Marvelous Mrs. Maisel](https://en.wikipedia.org/wiki/The_Marvelous_Mrs._Maisel) |
| Sample dates | 2022-03-11-to-2022-05-26 |
| Sample days | 77 |
| BTIH count | 150 |
| Unique BTIH count | 122 |
| Downloaders total | 1,577,852 |
| Uploaders total | 276,560 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-02T04:14:16Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/marvelous-mrs-maisel-407.xz`
- Hour directories: 1737
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (91 missing hours)
- Missing days: 3

### Sample archive discontinuities

- hourly gap: last `2022-03-18 22:00`, resumed `2022-03-22 18:00` — missing 91 hour(s)
- missing day: `2022-03-19`
- missing day: `2022-03-20`
- missing day: `2022-03-21`

## 3. Media objects file size histogram

![Marvelous Mrs. Maisel collection size histogram](figures/marvelous-mrs-maisel-407-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/marvelous-mrs-maisel-407-downloads-by-week-marvelous-mrs-maisel-407-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![marvelous-mrs-maisel-407 downloads by day](figures/marvelous-mrs-maisel-407-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.45 | 17.25 | 18.95 | 56.01 | 1.63 | 1.13 |

### Cumulative network infrastructure

[![Marvelous Mrs. Maisel cumulative map](figures/marvelous-mrs-maisel-407-carto.png)](figures/marvelous-mrs-maisel-407-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/marvelous-mrs-maisel-407-data-ge-1080p.webp)](figures/marvelous-mrs-maisel-407-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/marvelous-mrs-maisel-407-data-lt-1080p.webp)](figures/marvelous-mrs-maisel-407-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
