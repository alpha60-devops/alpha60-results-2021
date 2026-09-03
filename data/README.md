# Alpha60 results: year 2021 campaign

This directory holds the in-progress year-2021 Alpha60 results dataset. The
frozen campaign inventory contains 77 media objects at SHA-256
`99f6a7729bcfc0b62821b2f5ecf024379cc5c0a6611a87f5d779ea4c904841dc`.

## Campaign inputs

- `txt/year-2021-0-media-objects.txt`: canonical ordered inventory.
- `txt/year-2021-cache-aliases.tsv`: empty alias receipt; every canonical
  key maps directly to its same-named gold cache directory and member key.
- `txt/year-2021-cache-archive-overrides.json`: explicitly reviewed archive
  endpoint selections, if any.
- `txt/year-2021-cache-archive-map.json`: exact archive paths, sizes,
  SHA-256 identities, canonical sample contracts, sparse intervals, and
  byte-balanced ord/eureka ownership.

Cache archives and raw samples are immutable external campaign inputs and are
never committed to this repository. Generated data, figures, audit pages, and
the final checksum/release manifests are added only by the verified campaign
pipeline.
