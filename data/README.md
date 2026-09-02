# Alpha60 results: year 2022 campaign

This directory holds the in-progress year-2022 Alpha60 results dataset. The
frozen campaign inventory contains 63 media objects at SHA-256
`4b23d5579c1c0b49b0e1e96dd2421f2ca54e4e900753764f11b2fb87841a1791`.

## Campaign inputs

- `txt/year-2022-0-media-objects.txt`: canonical ordered inventory.
- `txt/year-2022-cache-aliases.tsv`: empty alias receipt; every canonical
  key maps directly to its same-named gold cache directory and member key.
- `txt/year-2022-cache-archive-overrides.json`: explicitly reviewed archive
  endpoint selections, if any.
- `txt/year-2022-cache-archive-map.json`: exact archive paths, sizes,
  SHA-256 identities, canonical sample contracts, sparse intervals, and
  byte-balanced ord/eureka ownership.

Cache archives and raw samples are immutable external campaign inputs and are
never committed to this repository. Generated data, figures, audit pages, and
the final checksum/release manifests are added only by the verified campaign
pipeline.
