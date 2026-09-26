# Self-hosted Basemap

The repository includes `hamilton.pmtiles`, a Hamilton bbox extract from the Protomaps
20260712 build, for the default offline MapLibre basemap:

```text
gui/frontend/public/basemaps/hamilton.pmtiles
```

The extract covers `175.1771,-37.8496,175.3555,-37.6735` at zoom levels 0–15. It is
derived from OpenStreetMap data; retain the OSM attribution shown in the archive metadata
when redistributing it. The GUI falls back to a muted blank canvas if the file is absent.
