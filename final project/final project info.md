# Comm-260 Final Project: Analysis of Homeschooling in the U.S. Story Pitch and Data Visualizations

## By Sophie Liebeck, Sara Voneisengrein, and Caroline Jones

### Steps used to analyze the data

1. We began by assembling our data sets; sources can be found below. There was a column in one of the sets that featured geography information, with both district and state appearing in the same column. We used "text to columns" in Excel to seperate these into two columns by the comma that separated the district from the state.
2. We then looked through the key from the NCES data to decide what demographics we wanted to use for this project. We chose to focus on race.
3. We chose 7 rows of demographic data related to race that we wanted to evaluate in this assignment. They were: total population of district, white population percentage, Black and African American percentage, American Indian and Alaska Native percentage, Asian percentage, native Hawiian and other Pacific Islander percentage, and two or more races percentage. We added these as column headers to a new data set.
4. We built a new data set that merged data from both sources to have demographic data on related to counts of homeschool students per district.
5. Then, we had all the data together in one data set: county name, state, LEA ID, homeschool population, and demographics.
6. At this point, we realized that we did not have the resources to manually add every disrtict in the country to our new data set, so we decided to work based off of a random sampling. We used ChatGPT to create a sample of 25 line items on the original data, and then manually added those to our new spreadsheet.
7. After this, we realized that the count of homeschool students per district would not paint an accurate picture of the data because districts can have different populations. To fix this problem, we divinded the count of homeschool students by the total population in the district to find the percentage of homeschool students in each district. That way, we had a more accurate picture of the data.
8. From there we used the "Sort" function on Excel to sort our data set in a few different ways to help us assess what our findings were: by highest to lowest percentage of homeschool students, by highest to lowest white population, and by highest to lowest black population.
9. Finally, we utilized data visualizations to help us see our findings in a clearer way, so we could understand what we needed to report.

### Findings from the data

Our main finding when we analyzed the data was that districts with a higher population of home schooled students are more likely to have a majority white population. Looking at the data, there are four districts with a homeschool population over 1%, and three of those districts are over 70% white. While the district with the highest population of homeschool students – Marshall County School District, MS with 1.77% – is only 61.5% white, followed by 30.2% black, this is the biggest outlier. The next three highest districts, all still with a home school population over 1%, are 70.6%, 93.5%, and 85.2% white. Further, Downey Unified School District in California has the population that is the least white, at only 36.3%, and also has the lowest homeschool population at just 0.06%. As for the data visualization, the data is heavily skewed left, with a heavy concentration of data points indicating high white populations. While this is just a random sample of 25 districts from across the country, this data does confirm our hypothesis that white populations are more likely to homeschool their children than populations of color.

#### Proposed nut graf

### Data sources

1. [Count of homeschool students by district, Washington Post](https://github.com/washingtonpost/data_home_schooling/blob/main/home_school_district.csv) - We used the most recent count from each district (2021-2023)
2. [Demographic Data by district, National Center for Education Statistics](https://nces.ed.gov/programs/edge/TableViewer/acsProfile/2022) - This data is from 2018-2022

### Plans for how you would report and structure this story if given more time

