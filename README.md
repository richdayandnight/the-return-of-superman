# The Return of Superman (TRoS)
This repository contains scripts and datasets used to make a visualization of [The Return of Superman data](https://public.tableau.com/views/TheReturnofSupermanTRoSKorea/TROSStory?:display_count=y&:origin=viz_share_link). 

# Contents
1. Jupyter notebooks used to scrape and clean data from The Return of Superman (TRoS) Wikipedia pages ([1](https://en.wikipedia.org/wiki/The_Return_of_Superman_(TV_series)), [2](https://en.wikipedia.org/wiki/List_of_The_Return_of_Superman_episodes)) and [TRoS TVDB Api](https://www.thetvdb.com/series/the-return-of-superman). 
2. Collected TRoS data saved in the data folder

# File Directory
- Scraping Cast of TRoS.ipynb
  - scrapes & cleans cast of TRoS
- Scraping The Return of Superman Data.ipynb
  - scrapes & cleans episode data of TRoS
- Family_csv.ipynb
  - outputs csv of cast appearances per episode
- data
  - sc_episodes.csv, fc_episodes.csv, cc_episodes.csv
    - contains special, former, and current cast timeline data
  - episodes_df.csv
    - contains episodes data (title, description, ratings, date aired, etc)
  - formerNarrator.csv, currentNarrator.csv
    - contains narrator data
  - specialCast.csv, formerCast.csv, currentCast.csv
    - contains personal data of special cast, former cast, and current cast (family name, occupation, age, etc)
  - cc_encoded.csv , fc_encoded.csv, sc_encoded.csv, total_encoded.csv(concat of the previous csv's)
    - contains cast appearances per episode
  - guests_df.csv, guest_df_prep.csv
    - contains guests data (guest_df_prep is the output csv after using Tableau Prep)
    
# Tools used
- Jupyter
- Tableau

## [Visualization of The Return of Superman](https://public.tableau.com/views/TheReturnofSupermanTRoSKorea/TROSStory?:display_count=y&:origin=viz_share_link)
