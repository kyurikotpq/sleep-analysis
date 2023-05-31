# Pei Qi Tea's Sleep Analysis

In 2016, in order to keep up with school work and study for the secondary school national examinations, I forced myself to sleep less than 6.5 hours a day. Despite trying to sleep more in high school and college, I realized that I would always wake up at around the 6-hour mark. Even if I managed to sleep 7 hours or more, I always woke up feeling more exhausted than the day before.

This repository contains my analysis, visualization, and interpretation of my sleep data using Python.

## Data collection methods

### Heart rate and sleep data
Over a period of ~6 months (July 1, 2022 to January 26, 2023), I tracked my sleep using my Xiaomi Mi Band 5 smartwatch. The exported data can be found in the `raw-data/` folder.

> There are some days where I didn't wear my watch to sleep; I will account for that when cleaning my data.

### Period data
Since February 2022, I also manually tracked the first day of my period in Google Calendar. I have compiled the data in a CSV file, also in the `raw-data/` folder.

### Exercise data
Finally, in September 2022, I started exercising more vigorously and regularly, through twice-weekly Hapkido sessions. While I didn't wear my watch during classes (so my heart rate wasn't tracked), I kept track of which days the sessions happened in Google Calendar. I have also compiled the data in a CSV file, also in the `raw-data/` folder.

## Questions to explore

- Is my sleep quality truly as poor as I feel it is?
- Is deep sleep affected by starting sleep time? Or is deep sleep more strongly correlated with the absolute hours of the night?
- Is deep sleep affected by which stage of the menstrual cycle I'm currently in?
- Does intense exercise (i.e. Hapkido sessions) increase the amount of deep sleep?


