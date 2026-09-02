# Cache coverage report — eternals

- Generated: 2026-09-02T04:14:13Z
- Sample archive directory: `/run/media/bkoz/gold/src/alpha60-samples-raw.gold/eternals.xz`
- Hour directories: 2434
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 2 (82 missing hours)
- Missing days: 3

## Sample archive discontinuities

- hourly gap: last `2022-02-04 14:10`, resumed `2022-02-08 01:03` — missing 81 hour(s)
- hourly gap: last `2022-03-27 01:03`, resumed `2022-03-27 03:03` — missing 1 hour(s)
- missing day: `2022-02-05`
- missing day: `2022-02-06`
- missing day: `2022-02-07`

## Review

Confirm the sampler state and disk capacity on the sampling
hosts for every zero-length file and discontinuity above
before treating the aggregate outputs as complete.
