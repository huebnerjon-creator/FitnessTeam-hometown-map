# Team Hometown & College Map

This is a lightweight reusable website prototype.

## How to run
Open `index.html` from a local web server. The easiest way:

1. Unzip the package.
2. Open a terminal in the unzipped folder.
3. Run: `python -m http.server 8000`
4. Open: `http://localhost:8000`

## How to add future teammates
Edit `data/team_members.json`.

Each teammate needs:
- name
- hometown city/state/lat/lng
- college name/city/state/lat/lng
- color
- optional college logo path

## How to add college logos
Put PNG files in the `logos` folder and update the `college.logo` value in `data/team_members.json`.

Example:
`"logo": "logos/university-of-central-fl.png"`

## Notes
Some team members currently have missing or ambiguous locations in the source spreadsheet, so they are included in the side list but not drawn until location data is completed.
