# DomainMap guided demo

DomainMap turns one validated dataset into an offline, read-only explorer for the architecture,
flows, contracts, data and deployment of a system. This repository holds a built copy of the
guided variant of the viewer, version 0.9.0-guided, with three fictional demo datasets. The guided
variant is a trial line kept apart from the releases, which are at
https://apostx.github.io/domain-map-demo/. It is published from each change to the variant; the
source is not public yet.

Try it at https://apostx.github.io/domain-map-guided-demo/ with one of the demos:

- [Town library](https://apostx.github.io/domain-map-guided-demo/#/home?dataset=library): three layers, a web front end, an API and a database, on
  two servers.
- [Online grocery](https://apostx.github.io/domain-map-guided-demo/#/home?dataset=grocery): thirteen components, an event bus and card payments,
  with production and staging.
- [Multi-currency wallet](https://apostx.github.io/domain-map-guided-demo/#/home?dataset=demo): half in the cloud, half on premises, with flows,
  contracts, data and coverage.

You can also open a dataset file of your own. The viewer runs entirely in your browser: it makes
no requests to other sites, and the files you open are never uploaded.

DomainMap is licensed under the Apache License 2.0 (see [LICENSE](LICENSE) and [NOTICE](NOTICE));
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) lists the licenses of the bundled packages.
