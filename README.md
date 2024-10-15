# Box-Office-Revenue
#### Business Task
This project is to look at box office movie revenues and profits. The movies being reviewed are from a variety of different genres that were released between 2012 and 2016.

The objective is to answer which genre generates the largest box office revenue in US dollars. An additional question to answer is "does higher box office revenue equate to higher profit margin?"

#### Sourcing and Cleaning Data
The data was sourced from Kaggle in excel format. The excel is shared above. From there, I used excel to find and remove all duplicates which resulted in zero duplicates being found. Looking over the raw data, there are empty cells, however, those are allowed due to the type of data being presented. Example being, the data contains two columns for genre and being notated as "Genre (1)" and "Genre (2)." The "Genre (1)" column required cell to be filled in while "Genre (2)" was allowed to either be filled in or blank as this would be a considered a subgenre. This also applied to the "Director" and "Cast" columns. 

#### Results
Once the data appeared to be presented in a clean format, the following step was to consolidate the financial data in order to answer the questions at hand. With the data being in excel format, a pivot table was chosen to consolidate. In this step, the following columns were chosen: "Genre," "Average of Box Office Revenue," "Average of Budget" and "Average of Profit." An additional column was created to show the "Average Profit Margin" percentage.

My expectation prior to this was Action/Adventure movies would generate the largest box office revenue. This was validated with the Adventure genre category commanding the largest revenue of $308m combined. Note that the  Action genre is a seperate category and is ranked sixth within this dataset. 

It is worth noting that the highest grossing film on its own is Despicable Me 2 which is a Comedy. Overall, Comedies rank ninth in box office revenue. 

As for the second question, "does higher box office revenue equate to higher profit margin?" The answer is no. Documentary and Horror genres have the largest proft margin at 85% and 81% respectively. 

### Recommendations
For studios and filmmakers looking to decide on what genre of movie to produce we need to look at what their financial goal is.
If a studio or filmmaker is wanting to gross the highest revenue, then they should explore an Adventure movie.
If they are looking to receive the highest return, producing a Documentary would be the best option.

### Limitations
The data reveiwed does present some limitations. The main issue is the time period the movies being reviewed. We are only looking at movies released between 2012 and 2016. A decade worth of movie box office revenues would provide a better sameple. This would take into account consumer preference changes as they aged along with consumers taste if studios oversaturated the market with one type of genre.

Another issue presented with this data is how it only looks at US films. A studio would need to understand who their main consumers are prior to deciding on genre as other parts of the world may have different preferences.  
