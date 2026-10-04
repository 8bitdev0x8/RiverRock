# Dublin Neighbourhood Signals

A single-page map for exploring Dublin service-request density on OpenStreetMap. The map shows heat only; individual complaint markers are not displayed.

## Run

Open `index.html` in a browser with an internet connection. Leaflet and OpenStreetMap tiles load from their public services.

## Load a CSV

Use the **Choose a CSV file** control in the app. Required columns:

- `lat` and `lon`, or `latitude` and `longitude`

An optional `STATUS` column (also accepts `incident_status` or `request_status`) enables the status filter. The heat radius is adjustable. The selected file is read in the browser; only coordinates and status are used. Other columns are ignored, and no complaint records are included in this repository.

Map data © OpenStreetMap contributors, [ODbL](https://www.openstreetmap.org/copyright).
