# DomainMap preview

DomainMap turns one validated dataset into an offline, read-only explorer for the architecture,
flows, contracts, data and deployment of a system. This repository holds the preview site for
changes on trial: 0.25.0 with four open changes, which are not released yet:

- a component's or a system's page draws the lines of one component at a time;
- the map can be narrowed by hand to some domains, systems and components (**Choose what to
  show** above the map), kept in the address;
- dataset format 0.8: glossary terms with topics, who uses them (common, industry, company)
  and a level from basic to expert; the glossary filters by them and downloads its terms as
  flashcards or a quiz;
- the dataset name stays readable in a crowded top bar.

The released viewer is at https://apostx.github.io/domain-map-demo/.

Try it at https://apostx.github.io/domain-map-guided-demo/#/?dataset=marketplace or on the
smaller https://apostx.github.io/domain-map-guided-demo/#/?dataset=demo. You can also open a
dataset file of your own; the viewer runs entirely in your browser, makes no requests to other
sites, and the files you open are never uploaded.

DomainMap is licensed under the Apache License 2.0 (see [LICENSE](LICENSE) and [NOTICE](NOTICE));
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) lists the licenses of the bundled packages.
