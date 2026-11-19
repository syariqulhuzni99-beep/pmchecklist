# PM Checklist System

## Run the app

Open `index.html` in a modern browser. An internet connection is needed to load
ExcelJS from its CDN and to generate Excel reports.

You can also keep `pm-workstation.html` as the single-file version.

## Data and OneDrive

Reports and templates are stored in the browser's local storage. They are
available only in that browser profile on that device; placing the app files in
a OneDrive-synced folder does not sync the browser data between devices.

Excel reports are downloaded by the browser. Upload them to OneDrive manually.
Automatic OneDrive upload and Microsoft sign-in are not implemented.

## Demo sign-in

The engineer PIN is `1234`. This is a temporary demo PIN, not secure
authentication. Do not use it to protect production or confidential data.
