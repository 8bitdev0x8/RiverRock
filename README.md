# Dublin Neighbourhood Signals

An OpenStreetMap heatmap for exploring Dublin service requests. The app shows heat only, with matching report summaries and a monthly trend chart.

## Run

Open `index.html` in a browser with an internet connection. Leaflet and OpenStreetMap tiles load from their public services.

## Load a CSV

Use **Choose a CSV file**. Coordinates are required as `lat`/`lon` or `latitude`/`longitude`. Optional fields power filters and report details:

- Issue: `issue`, `issue_type`, `problem`, or `NAME`
- Category: `category` or `GROUP_NAME`
- Report date: `reported`, `date`, or `INCIDENT_DATE`
- Location: `location`, `area`, `neighbourhood`, `postcode`, or `INCIDENT_ADDRESS`
- Status: `STATUS`, `incident_status`, or `request_status`

Issue, category, time, location and status filters update the heatmap, report list and trend together. The selected file is read in the browser; only these mapped fields are used. Names and incident IDs are ignored, and no complaint records are included in this repository. Recent-period filters use today as the reference date; use **All dates** to explore older sample records.

Map data © OpenStreetMap contributors, [ODbL](https://www.openstreetmap.org/copyright).
