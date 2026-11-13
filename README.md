# Teacher Talks 2026 — Results at a Glance

Dashboard of Teacher Talks 2026 results (RMIT Vietnam, SEUP).

- `index.html` — the page (charts drawn with d3, loaded from a CDN)
- `data/` — the CSV files behind every chart and number

## Update a number
Edit the matching CSV in `data/` and commit. The page reads the files each time it opens.

## Change colours or fonts
Edit the "Theme" block at the top of `index.html` (`--chart-1` … `--chart-5` are the chart colours).

## Preview on your own computer
Opening `index.html` by double-clicking won't load the data (browsers block that).
Use GitHub Pages, or run `python3 -m http.server` in this folder and open http://localhost:8000.
