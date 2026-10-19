# DomainMap preview

DomainMap turns one validated dataset into an offline, read-only explorer for the architecture,
flows, contracts, data and deployment of a system. This repository holds a preview build of the
viewer, 0.11.0 with three changes on trial. The released viewer is at
https://apostx.github.io/domain-map-demo/.

- **Domain matrix:** the domains against each other in a table. Try it at
  https://apostx.github.io/domain-map-guided-demo/#/home?dataset=demo&graph=matrix, or choose
  **Domain matrix** from the right-click view menu of the architecture.
- **Sticky levels:** zooming out a little keeps the components; **Keep this level** keeps the
  level whatever the zoom.
- **One label switch:** **Labels on the lines** shows or hides the labels on every level, and
  the labels say what the contracts describe.

You can also open a dataset file of your own; the viewer runs entirely in your browser, makes no
requests to other sites, and the files you open are never uploaded.

DomainMap is licensed under the Apache License 2.0 (see [LICENSE](LICENSE) and [NOTICE](NOTICE));
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) lists the licenses of the bundled packages.
