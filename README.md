# Dublin Neighbourhood Signals

A small web map for exploring Dublin City service request complaints. The app uses OpenStreetMap tiles and Leaflet, and accepts a CSV file containing coordinates and optional issue categories and dates.

## Run

Open `index.html` in a browser with an internet connection. Leaflet and the OpenStreetMap base map load from their public services.

## Import complaint data

Use the CSV upload control. Required columns:

- `latitude`
- `longitude`

Optional columns: `category` (or `issue_type`, `type`, `service_type`) and `date` (or `created_date`, `created`, `timestamp`).

The app plots uploaded records in the browser. No complaint data is included in this repository.

Map data © OpenStreetMap contributors, [ODbL](https://www.openstreetmap.org/copyright).
