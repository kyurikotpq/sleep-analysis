# Pei Qi Tea's Sleep Analysis

In 2016, in order to keep up with school work and study for the secondary school national examinations, I forced myself to sleep less than 6.5 hours a day. Despite trying to sleep more in high school and college, I realized that I would always wake up at around the 6-hour mark. Even if I managed to sleep 7 hours or more, I always woke up feeling more exhausted than the day before.

I finally got a smartwatch in January 2024 to investigate. This repository contains my analysis, visualization, and interpretation of my sleep data using Python.

## Data Description

### `data/shr_v_temp_phase.csv`

#### Heart rate (HR), Heart rate variability (HRV)
I've worn my Samsung Galaxy Watch 6 every night since I got it in January 2024. However, it wasn't until the Samsung Health app introduced "energy scores" on December 17, 2024 that I got easy access to my sleeping HR and HRV data.

#### Period & Basal Body Temperature data
I only have basal body temperature data from August 2024, and I used Samsung Health's ovulation predictions and manually-tracked period dates to determine the menstrual cycle phase for each day (follicular VS luteal).

### `data/daytime_naps.csv`
Contains the daytime nap sessions (sleep sessions that start between 6am and 6pm, recorded by Samsung Galazy Watch 6)

### `data/nighttime_sleep.csv`
Contains the nighttime sleep sessions recorded by Samsung Galazy Watch 6.
