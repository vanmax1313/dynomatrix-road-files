# DYNOMATRIX road files

Road files for the DYNOMATRIX Weather Map Lab app: the USA in 5 x 5 degree squares, in the BRouter format
(segments4, `.rd5`). The app downloads the squares a trip needs from the newest release:

    https://github.com/vanmax1313/dynomatrix-road-files/releases/latest/download/<square>.rd5

A square is named after its south-west corner: `W85_N35.rd5` covers 85-80 degrees W, 35-40 degrees N.

## Credits and license

- Map data (c) OpenStreetMap contributors, available under the Open Database License (ODbL) -
  https://www.openstreetmap.org/copyright
- The files are made by the BRouter project - https://brouter.de - https://github.com/abrensch/brouter -
  and copied unchanged from https://brouter.de/brouter/segments4 (each release says the date).
- These files are a database shared under the same ODbL license: you may use and share them, credit
  OpenStreetMap contributors, and keep any changed version under the ODbL.

## Place files

The same squares also have a place file - gas stations, restaurants and fast food, hotels and motels, rest areas,
campgrounds, motorcycle shops and ATMs - which the app uses to show places on the map, in its search and along a
route, with no signal:

    https://github.com/vanmax1313/dynomatrix-road-files/releases/latest/download/<square>.places.gz

`W85_N35.places.gz` is a gzip'd text file, one place per line (OpenStreetMap id, latitude, longitude, kind, name,
brand, address, phone, opening hours). `places.tsv` lists the files, their sizes and how many places each holds.

- Data (c) OpenStreetMap contributors, available under the Open Database License (ODbL) 1.0 -
  https://www.openstreetmap.org/copyright - https://opendatacommons.org/licenses/odbl/1-0/
- Made by DYNOMATRIX from Geofabrik's OpenStreetMap extract (https://download.geofabrik.de) - each file says the date.
- These files are a database shared under the same ODbL license: you may use and share them, credit
  OpenStreetMap contributors, and keep any changed version under the ODbL. Each file starts with the same notice.
