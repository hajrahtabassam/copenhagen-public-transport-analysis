# Copenhagen Public Transport Analysis

This repository analyzes public transport service levels in Copenhagen, using cleaned CSV data for buses, metro, trains, and trams. The analysis focuses on the number of services per hour throughout the day.

## Dataset

- `data/data.csv`: hourly service counts for each transport mode.
- Columns:
  - `hour` — hour of the day (0–23)
  - `transport_mode` — Bus, Metro, Train, Tram
  - `service_count` — number of scheduled services

## Analysis

- Plotted hourly service distribution for each mode.
- Calculated total daily services per transport mode.
- Identified peak hours for each mode.

## Results

- Bus and Metro dominate daily services, especially during morning (7–9 AM) and evening (4–6 PM) peaks.
- Train and Tram have fewer services but show similar peak patterns.
- The line plot below summarizes service intensity by hour:

![Hourly services](figures/hourly_services.png)

## Key Insights

- Peak commuting times are clearly visible across all modes.
- Bus and Metro have the most frequent service throughout the day.
- Train and Tram offer fewer services but remain consistent during peak periods.

## Future Work

- Incorporate multi-day datasets to study weekday vs weekend trends.
- Combine with passenger count data to calculate load factors.
- Extend analysis to compare pre- and post-COVID service patterns.
