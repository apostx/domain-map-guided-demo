# DomainMap preview

DomainMap turns one validated dataset into an offline, read-only explorer for the architecture,
flows, contracts, data and deployment of a system. This repository holds a preview build of the
viewer: 0.13.0 with the next changes to selecting on the map, hidden domains, and a flow drawn
with only its components on trial. The released viewer is at https://apostx.github.io/domain-map-demo/.

- **What is selected stays lit.** Pointing at another component or domain previews its lines
  lightly, without labels; the inspector stays with the selection.
- **Clearing.** A click on an empty part of the map, or Escape, clears the selection; moving the
  map does not.
- **Every level shows the selection.** Zoomed out, a selected component is its domain, which
  names it, and its own lines rolled up into bands; zoomed in, a selected domain lights its cards
  and the lines that cross its border.
- **Selecting a domain does not zoom.** A double click on its box, or **Zoom to** in the
  inspector, zooms to it.
- **Hidden domains.** **Domains 13/13** on the map opens a list to tick; a domain's right-click
  menu offers Hide, Show only it and its neighbours, and Focus. Hidden domains are left out of
  every page until **Show all** beside the perspectives.
- **On trial: a flow with only its components.** Right-click the route and choose **With only
  its components**: the domains in the order the flow reaches them, the components of every way,
  those off the way shown dimmed. For example
  https://apostx.github.io/domain-map-guided-demo/#/flow/place-order?dataset=marketplace&route.scope=flow

Try them at https://apostx.github.io/domain-map-guided-demo/#/?dataset=marketplace or on the
smaller https://apostx.github.io/domain-map-guided-demo/#/?dataset=demo. You can also open a
dataset file of your own; the viewer runs entirely in your browser, makes no requests to other
sites, and the files you open are never uploaded.

DomainMap is licensed under the Apache License 2.0 (see [LICENSE](LICENSE) and [NOTICE](NOTICE));
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) lists the licenses of the bundled packages.
