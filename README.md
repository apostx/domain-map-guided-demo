# DomainMap preview

DomainMap turns one validated dataset into an offline, read-only explorer for the architecture,
flows, contracts, data and deployment of a system. This repository holds a preview build of the
viewer, 0.11.0 with two changes on trial. The released viewer is at
https://apostx.github.io/domain-map-demo/.

- **Sticky levels:** zooming out a little keeps the components; **Keep this level** keeps the
  level whatever the zoom.
- **One label switch:** **Labels on the lines** shows or hides the labels on every level; a
  closed label says how many interactions a line stands for, and what the contracts describe.

Try them at https://apostx.github.io/domain-map-guided-demo/#/?dataset=demo. You can also open
a dataset file of your own; the viewer runs entirely in your browser, makes no requests to other
sites, and the files you open are never uploaded.

DomainMap is licensed under the Apache License 2.0 (see [LICENSE](LICENSE) and [NOTICE](NOTICE));
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) lists the licenses of the bundled packages.
