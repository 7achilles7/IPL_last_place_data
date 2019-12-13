# IPL_last_place

The region and the domain category for the data :
Cricket(Sports),India


Research question about the domain category and region:
How ranks of 7 major teams in Indian Premier League(IPL) change from its commencement in 2008 till 2019?


Data Source : https://en.wikipedia.org/wiki/List_of_Indian_Premier_League_seasons_and_results#cite_note-IPL_2019_points_table-34

Final Visual : IPL Team Ranks corelation.jpeg


In this analysis and visualization, the correlation among ranks is shown for different IPL Teams. The data from Wikipedia was used for this analysis and comparison. The original data consist of 13 teams but some of them didn't play for most of the seasons, either they started playing late or got suspended after few years of playing. Therefore, data for 7 major teams, who were not absent for more than 2 seasons, is taken into consideration, namely, Royal Challengers Bangalore, Rajasthan Royals, Mumbai Indians, Kolkata Knight Riders, Kings XI Punjab, Delhi Capitals, Chennai Super Kings. Among these, Rajasthan Royals and Chennai Super Kings, were the 2 teams who were not there for 2 seasons(2016 and 2017).

The plot is a line graph whose x-axis depicts season's years and y-axis give position values for all teams. For Visualization, matplotlib and ggplot style is used.
The graph reveals that Chennai Super Kings have dominated almost all other teams in the years that they played. Whereas, for Kolkata Knight Riders and Delhi Capitals we can observe too much range in their ranks. Mumbai Indians started low in 2008 but went on to win the competition 4 times (in 2013,2015,2017,2019). Kings XI Punjab always remained in between other teams with a lot of ups and downs.

To implement Cairo's principle of truthfulness excess data with missing data was removed.
To implement Cairo's principle of beauty ggplot style of matplotlib was used.
Pandas and numpy libraries were used to generate functional insights from data.

The visual also addresses Cairo's principles of truthfulness, functionality, beauty, and insightfulness.
