# Box-Office-Revenue
#### Business Task
This project is to look at box office movie revenues and profits. The movies being reviewed are from a variety of different genres that were released between 2012 and 2016.

The objective is to answer which genre generates the largest box office revenue in US dollars. An additional question to answer is "does higher box office revenue equate to higher profit margin?"

#### Sourcing and Cleaning Data
The data was sourced from Kaggle in excel format. From there, I used excel to find and remove all duplicates which resulted in zero duplicates being found. Looking over the raw data, there are empty cells, however, those are allowed due to the type of data being presented. Example being, the data contains two columns for genre and being notated as "Genre (1)" and "Genre (2)." The "Genre (1)" column required cell to be filled in while "Genre (2)" was allowed to either be filled in or blank as this would be a considered a subgenre. This also applied to the "Director" and "Cast" columns. 

#### Allowing Data To Tell The Story
Once the data appeared to be presented in a clean format, the following step was to consolidate the financial data in order to answer the questions at hand. With the data being in excel format, a pivot table was chosen to consolidate. In this step, the following columns were chosen: "Genre," "Average of Box Office Revenue," "Average of Budget" and "Average of Profit." An additional column was created to show the "Average Profit Margin" percentage.

My expectation prior to this was Action/Adventure movies would generate the largest box office revenue. This was validated with the Adventure genre category commanding the largest revenue of $308m. Note that the  Action genre is a seperate category and is ranked sixth within this dataset. 
