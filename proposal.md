# Project Proposal: Big Waves on California's Central Coast

**Author:** Johnny Peschong

## Research Question

How often does California's Central Coast get really big waves, how big do the biggest swells get, and what months do they usually happen in?

## Why It Matters

Surfers on the Central Coast talk a lot about "big-wave season," but most of that is based on memory and stories. Wave data can show how often big swells actually happen and when. This matters for surfers, but also for beach safety, lifeguards, and coastal planning, since big swells can be dangerous and cause erosion.

## Data Source

I plan to use historical wave data from NOAA's National Data Buoy Center (NDBC). NDBC buoys off the Central Coast record wave height, wave period, and wave direction about every hour, and their historical data is free to download. I'll pick one or two buoys near the Central Coast and use as many years of data as are available.

Main variables:
- **Significant wave height (WVHT):** the average height of the biggest third of the waves
- **Dominant wave period (DPD):** time between waves, which shows how powerful a swell is
- **Date and time:** to group the data by month and season

## Methods

1. Download the historical buoy data files for the years I choose.
2. Clean the data by removing missing values (NDBC uses codes like 99.0 for missing data).
3. Define a "big wave" day as a day where wave height goes over a set threshold (for example, 4 meters).
4. Count big-wave days per year and per month.
5. Find the biggest swells on record and when they happened.
6. Make charts showing which months get the most big waves.

## Possible Challenges

- Buoys sometimes break or go offline, so there may be gaps in the data.
- Wave height at a buoy offshore isn't the same as wave size at the beach.
- Picking a "big wave" threshold is a judgment call, so I may test more than one.

## Expected Outcome

I expect most big-wave days to happen in winter (around November through March), when big storms in the North Pacific send swells to California. The data will show if that's true and how often the really big swells actually happen.
