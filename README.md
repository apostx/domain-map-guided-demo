# DomainMap preview

DomainMap turns one validated dataset into an offline, read-only explorer for the architecture,
flows, contracts, data and deployment of a system. This repository holds the preview site for
views on trial: the released 0.17.0, with an inventory page on trial that also holds what the
coverage page showed. The released viewer is at https://apostx.github.io/domain-map-demo/.

- **Inventory.** Every component in one table: its domain, kind, technology, coverage and what
  it rests on, lifecycle, where it runs, its protocols and its contracts; above it how many are
  covered, below it the sources. The filters of the top bar narrow
  it and take it to the map; a search and the lifecycle and contract filters narrow it here;
  a column's header sorts by it. Try
  https://apostx.github.io/domain-map-guided-demo/#/inventory?dataset=marketplace

You can also open a dataset file of your own; the viewer runs entirely in your browser, makes no
requests to other sites, and the files you open are never uploaded.

DomainMap is licensed under the Apache License 2.0 (see [LICENSE](LICENSE) and [NOTICE](NOTICE));
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) lists the licenses of the bundled packages.
