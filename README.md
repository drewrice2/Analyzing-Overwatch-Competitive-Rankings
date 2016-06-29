# Analyzing-Overwatch-Placement-matches

This project sought to analyze the distribution of players' ranks after opening day of Overwatch's competitive mode. The players polled were from reddit.com/r/CompetitiveOverwatch. Nearly 2,000 responses came in during the first 6 hours, so a quick analysis method was needed. I threw the data (included in the repo) into a notebook, cleaned the data, and plotted the distribution.

A Jupyter Notebook was the best choice for the job to easily generate and read summary statistics. Graphing on new data was very straightforward too. Every half hour or so, I reran the script on the new data in order to update the notebook. The data cleaning was necessary due to some troll responses such as string data and values outside of the expected range. Finally, I updated the repo after each run of the script in order to share the info with reddit.

The data is available from this repo in .csv format. WARNING: some of the troll responses are explicit.
