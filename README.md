# DomainMap demo

DomainMap turns one validated dataset into an offline, read-only explorer for the architecture,
flows, contracts, data and deployment of a system. This repository holds a built copy of the
viewer, version 0.20.0, with four fictional demo datasets. It is published from each
release; the source is not public yet.

Try it at https://apostx.github.io/domain-map-demo/ with one of the demos:

- [Town library](https://apostx.github.io/domain-map-demo/#/home?dataset=library): three layers, a web front end, an API and a database, on
  two servers.
- [Online grocery](https://apostx.github.io/domain-map-demo/#/home?dataset=grocery): thirteen components, an event bus and card payments,
  with production and staging.
- [Multi-currency wallet](https://apostx.github.io/domain-map-demo/#/home?dataset=demo): half in the cloud, half on premises, with flows,
  contracts, data and coverage.
- [Online marketplace](https://apostx.github.io/domain-map-demo/#/home?dataset=marketplace): about 230 components in twelve domains, talking
  over APIs and an event bus; how a large system reads.

You can also open a dataset file of your own. The viewer runs entirely in your browser: it makes
no requests to other sites, and the files you open are never uploaded.

DomainMap is licensed under the Apache License 2.0 (see [LICENSE](LICENSE) and [NOTICE](NOTICE));
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) lists the licenses of the bundled packages.
