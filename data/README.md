# Data Directory

This directory contains the processed data used in the Copenhagen Public Transport Analysis.

## Processed CSV

- `data.csv` — clean dataset with hourly service counts for each transport mode (Bus, Metro, Train, Tram).

## Notes on Raw Data

- The original GTFS files from Rejseplanen were large and are **not included** in this repository to avoid exceeding GitHub size limits.
- `data.csv` was extracted and aggregated from these raw GTFS files.
- Any further analysis should use `data.csv` directly.

## File Structure

- `data.csv` — final cleaned and aggregated dataset used for analysis.
