# Run-Project-Data (private)

Personal data for the trail-map project (code: https://github.com/Julesbor38/RunProject).

- `strava-export/` : full Strava archive export (activities, media, profile, CSVs) + original zips
- `trail-map-data/` : contents of `trail-map/data/` (raw tracks, privacy zones, OSM/DEM/activity caches)

## Restore on a new machine
    git clone https://github.com/Julesbor38/RunProject.git trail-map
    git clone https://github.com/Julesbor38/Run-Project-Data.git
    cp -a Run-Project-Data/trail-map-data/. trail-map/data/
