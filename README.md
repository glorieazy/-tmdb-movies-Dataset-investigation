## 'tmdb-movies' Dataset investigation
This project is mainly carried out to test the ability on data investigation.
### Dataset 
The Dataset consists of observations of different movies and their interactions with its audience. The Dataset consists of **10866 observations and 21 variables** such as: movie ids, movie popularity, budget, revenue, producing companies, genre, release date, votes and host of others. There are many categorical variables as much as the numerical variable in the dataset.
### Summary of Findings
After the dataset is thoroughly wrangled, the following key insights are generated:
- The number of Movies produced increases as the Year passes by, the lowest number Movies was produced in 1960, while the highest number of movies was produced in few years before 2015. A cause of this could have been technological advancement.
- There are more profitable production than loss. Over 7000 movies yield prositive returns(Profits) of investment which is over 50% of the total productions, while less than 4000 productions yield negative returns(Loss)
- The longer the runtime of a Movie, the returns is decreasing, 9 out of the ten longest movies yield negative returns(Loss).
- The more popular a movie is, there is tendency it will yield positive return. According to this dataset, the 10 most popular movies yield positive Returns.
- The month of June has the highest average return followed by May and December.
- The Year 1995 has the highest average yearly generated Returns while the year 1966 has lowest yearly average generated Returns.
- The month of September has the highest number of produced movies, in this month, most of the produced movies yield more postively than negatively. While, the month of February has the lowest number of produced Movies, in this month also, most of the production yielded more positively (profits) than negatively(Loss).

- Correlated columns: The columns are correlatively checked, some has very strong correaltions while some also have low correlations, below explains that better:

> Budget and Popularity (Moderately correlated)
Budget and Vote counts (Strong correlated)
Budget and Returns (Moderately Correlated)
Popularity and Vote counts (Very Strong Correlation)
Vote counts and Return (Very Strong Correlation)
Returns and Popularity (Strong Correlation)
Popularity and Runtime (Low Correlation)
Budget and Runtime (Low Correlation)
Vote counts and Runtime (Low Correlation)
Returns and Runtime (Low Correlation
