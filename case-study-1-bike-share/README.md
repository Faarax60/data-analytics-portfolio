# Case Study 1: How does a bike-share navigate speedy success?

## Business Task
How do annual members and casual riders use Cyclistic bikes differently, and how can Cyclistic convert casual riders into annual members?

## Data Sources
Cyclistic trip data: 12 monthly CSV files, October 2025 to September 2026, with one row per ride.

## Cleaning
- Combined the 12 files into one dataset of 6,171,785 rides.
- Calculated ride length (end time minus start time) and day of week.
- Removed 5,353 rides with zero, negative, or over-24-hour durations.
- Kept 6,166,432 rides for analysis.

## Analysis Summary
- Members make up 64.6% of rides; casual riders make up 35.4%.
- Casual rides are longer: 17 min 34 s on average, compared with 11 min 56 s for members.
- Members ride most on weekdays, peaking on Wednesday.
- Casual riders peak on Saturday, when they account for 47.7% of rides that day.
- Both groups ride most in summer. Casual rides rise from 24,656 in January to 357,121 in July.

## Visualisation
[Casual vs Member Rides by Day](https://public.tableau.com/app/profile/faarah.furan.mohamed/viz/CyclisticcasualvsMemberRides/Sheet1)

## Recommendations
1. Offer weekend and summer membership deals to casual riders.
2. Promote commuter benefits to members on weekdays.
3. Launch membership campaigns in spring, before the summer peak.
