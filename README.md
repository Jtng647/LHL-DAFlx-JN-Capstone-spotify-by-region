# Capstone Project: Spotify By Region

## Project/Goals
The main objective of this project was to make use of all the data analytical skills, tools, and knowledge obtained over the course of the Data Analytics Flex program. The problem it is being applied to is how to make use of a Spotify Dataset to gather insight that can be used in real-world contexts, and present it visually in a dashboard that would be intuitive and informative for both potential employers and the public.

## Process
### Step 1:
The first step was to acquire the Spotify dataset and prepare it for use. Python (via a Google Colab notebook) was applied here to ensure the data cleaning was efficient, accurate, and consistent. The data cleaning included removing trailing spaces in text, ensuring data type as required (date, int, string, region), and removing nulls and invalid entries with missing data.

### Step 2:
The second step was to load/connect the data to Tableau, and build the visualizations that could then be compiled into Dashboards for presentation. A map view, Artist/Song-to-Stream No. comparisons, and an Artist-centric analysis scatter plot and line graph were all generated using the data set. Since this data spans 2017 (Jan. 2017- Jan. 2018), an animated timeline was applied to several of these visualizations to model the change over time as well.

## Results
The [resulting dashboards](https://public.tableau.com/app/profile/josh.ng4033/vizzes) modeled many relationships and correlations that could provide insights useful for real world applications. Marketing strategies, decisions, and forecastiing could be determined by using the trends scene in this data.

## Challenges 
A dataset as large as this requires much more powerful hardware to process efficiently, than was available. Initially, the dataset that was planned to be used was a ~4 Gb CSV file with over a million lines of entries. Tableau could not open the file, and Python was slow to process through all of it. Even the dataset that ended up being used, being a 100 Mb file, would cause Tableau to take some time to process when generating and sorting its visuals.

## Future Goals
The number of conclusions that could be drawn was only limited by the time and extent to which one could commit to peruse them. With more time to build these visualizations, their functions can become more robust and polished. Further improving their efficacy, and therefore, value.
