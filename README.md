# TSI Trip planner (prototype)

Standalone mill-visit trip planner — **mock data only, no keys, no customer data**.
This is a published mirror of `travel-planner.html` from the private `tsi-intel`
repo, hosted so it can be tested by reloading a page.

- **Live:** https://tealninja.github.io/tsi-trip-planner/
- Source of truth is `tsi-intel` (branch `claude/mill-visit-travel-planner-jog1rm`);
  this repo is refreshed on each change.

Open `index.html` locally to run it too — the map (Leaflet), geocoder (Photon),
and routing (OSRM / optional OpenRouteService) need a connection; the planner
logic works offline.
