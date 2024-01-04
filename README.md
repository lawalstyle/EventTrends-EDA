# EventTrends-EDA

## Project Overview
EventTrends-EDA is a data analysis project that explores the intricacies of music and speaker event schedules from the 2019 SXSW festival. The analysis dives into the frequency of events, genre popularity, event timing, and key themes from event descriptions.

## Features
- **Data Cleaning**: Implements preprocessing techniques to handle missing values and prepare the datasets for analysis.
- **Data Visualization**: Offers a variety of plots and charts to illustrate the distribution and frequency of events.
- **Time Analysis**: Categorizes events into time slots to understand daily event patterns.
- **Word Cloud Generation**: Creates visual word clouds to identify the prominence of themes within speaker event summaries.

## Datasets
The project uses two primary datasets:
1. `music_schedule_2019.csv` - Contains information about music events, including genres, artists, and event times.
2. `speaker_schedule_2019.csv` - Lists speaker events with details on speakers, titles, and summaries.

## Tools Used
- **Pandas**: For dataset manipulation and analysis.
- **Matplotlib/Seaborn**: For creating static, interactive, and informative visualizations.
- **WordCloud**: For generating word clouds from text data.

## Installation
To set up the project environment, you need Python 3.x and the following packages:
```bash
pip install pandas matplotlib seaborn wordcloud
