# Neighbourhood Signals

A general-purpose OpenStreetMap heatmap for exploring community service requests in any area. It combines an interactive heatmap with issue, category, time, location, and status filters, matching report summaries, and a monthly trend chart.

## Run

Open `index.html` in a browser with an internet connection. Leaflet and OpenStreetMap tiles load from their public services. Load a dataset with coordinates to zoom directly to its coverage area.

## Load a CSV

Use **Choose a CSV file**. Coordinates are required as `lat`/`lon` or `latitude`/`longitude`. Optional columns power filters and report details:

- Issue: `issue`, `issue_type`, `problem`, or `NAME`
- Category: `category` or `GROUP_NAME`
- Report date: `reported`, `date`, or `INCIDENT_DATE`
- Location: `location`, `area`, `neighbourhood`, `postcode`, or `INCIDENT_ADDRESS`
- Status: `STATUS`, `incident_status`, or `request_status`

The selected file is read in the browser; only mapped fields are used. Names and incident IDs are ignored, and no complaint records are included in this repository. Recent-period filters use today as their reference date; choose **All dates** to explore older records.

Map data © OpenStreetMap contributors, [ODbL](https://www.openstreetmap.org/copyright).
