# Binnatex Container Management V14

This version imports the full set of 31 container rows found in the supplied `BTX ETA.xlsx` workbook into the Import list automatically on startup. It does not require an O.T.W. button. It preserves existing records and updates missing manifest fields for matching container numbers.

The spreadsheet's loading date is stored as ETD and the ETA, supplier, booking agent, container number, item descriptions and weights are imported. Item quantities were not present in the source workbook and are left at zero.

Replace the project's `index.html` with this file on GitHub Pages. This app uses browser local storage; this is not cloud sync.
