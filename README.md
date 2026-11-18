[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.on007714-blue)](https://doi.org/10.82901/nemar.on007714)

<!-- nemar:provenance -->
## Provenance

This dataset is mirrored on NEMAR from OpenNeuro.

- Source: [ds007714](https://openneuro.org/datasets/ds007714)
- DOI: [10.18112/openneuro.ds007714.v1.0.0](https://doi.org/10.18112/openneuro.ds007714.v1.0.0)

## Data notes

- `sub-s45/nirs/sub-s45_task-visual_nirs.snirf` is truncated in OpenNeuro ds007714 1.0.0: the published file holds
  7,771,051 bytes (size in its git-annex key), while its HDF5 superblock gives an end-of-file address of 14,432,504
  bytes, so HDF5 readers report a truncated file (source: the published file itself).
- 42 of the 64 `*_events.tsv` files are not sorted by onset (BIDS validator warning EVENT_ONSET_ORDER; counted in
  the events.tsv files of this dataset).
