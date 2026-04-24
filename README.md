# Spotify Analytics Dashboard

## Overview
Built an interactive Power BI dashboard to analyze track, artist, and album performance using Spotify dataset. The dashboard provides insights into track popularity, artist contribution, album distribution, explicit vs non-explicit content, and release trends over time.

## Data Model
Designed using Star Schema:
- Fact Table: Main Table
- Dimension Tables:
  - dim_artist
  - dim_album
  - dim_track
  - date_tbl

Relationships were created using:
- track_id
- artist_id
- album_id
- album_release_date :contentReference[oaicite:1]{index=1}

## DAX Measures Used
- Total Tracks
- Total Artists
- Total Albums
- Average Track Popularity
- Maximum Track Popularity
- Average Track Duration
- Explicit Count
- Non-Explicit Count
- Selected Artist using SELECTEDVALUE()

## Visuals Used
- KPI Cards
- Bar Charts
- Column Charts
- Donut Charts
- Stacked Charts
- Tree Map
- Scatter Plot
- Matrix Table
- Line Chart
- Gauge Chart
- Tables
- Slicers :contentReference[oaicite:2]{index=2}

## Key Analysis
- Top 10 Artists by Popularity
- Top Tracks by Popularity
- Tracks by Album Type
- Explicit vs Non-Explicit Content
- Popularity vs Duration Analysis
- Album Release Trends Over Time
- Artist-wise Track Distribution

## Tools Used
- Power BI
- DAX
- Power Query
- Data Modeling
- Excel Dataset

## Outcome
Converted raw Spotify data into meaningful business insights using advanced visuals, DAX measures, and interactive reporting features.

## Author
Arya Nair
