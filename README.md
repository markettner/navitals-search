# navitals-search

Offline search indexes for the Navitals app: one SQLite file per region, so addresses, streets,
places and points of interest can be found on the phone with no signal. Built monthly from the
same Geofabrik extracts as the routing packs in
[navitals-packs](https://github.com/markettner/navitals-packs).

- One rolling release, `search`, with one `<region>.search.sqlite.gz` per region. Files are
  replaced in place on each monthly update, so download URLs stay stable. Checksums and sizes
  are in the Navitals pack index.
- Total release size is kept under 5 GB.

Map data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, available under
the Open Database License (ODbL).
