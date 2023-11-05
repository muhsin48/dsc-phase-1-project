

# Showtime Success: Microsoft's Film Studio Strategy through Data

**Author**: [Muhsin Ahmed Abdule](mailto:muhsin.ahmed@student.moringaschool.com)

## Project Overview

In this project , I aim to provide actionable insights to Microsoft which is venturing into the film industry through establishing a new studio.Microsoft is a giant in the technology sector however they lack experience when it come to the film industry.The projects's Objectives is to explore the movie industry and identify which film types are doing the best at the box office

### Business Problem

The main business problem is that Microsoft wants to venture into a competitive Market without the prior experience of the industry.To address the problem,this project explores and answers several questions to provide actionable insights:

Which genre selection are currently the most successful?
Is there a Relationship between Profits and movie budgets?
Is there a Relationship between Rating,number of votes and profits made?
What is the trend of profits across years?

### Data understanding

The data used for this project comes from the following websites:

1.IMDB: i used the IMDB to access two datasets i.e imdb.title.basics that contains fundamental information about movies,imdb.title.ratings that contains rating information about movies

2.Box Office Mojo (BOM):I used the bom.movie_gross that contains earnign values for movies at the box office

3.The Numbers (TN): tn.movie_budgets this dataset contains information on the production budget

These datasets are relevant to our data analysis questions.They allow us to explore and the film industry in relation to its financial success and other aspects.The data provides insights that can guide Microsoft's studio to create new films and  navigate through the film industry and make huge profits

The data represents movies with each row corresponding to a unique film.The sample include wide range of movies from different Genres,Start_year and production Budgets

The Target variable for this analysis is on  the Profit Made which can be calculated through analysis of the box office and the production Budgets
properties of the key variables include:
The imdb.title.basics dataset includes variables like movie titles, genres, and Start years.
The imdb.title.ratings dataset provides information about movie average_rating and the number of votes
The bom.movie_gross dataset contains variables for movie titles, studio names, and domestic and foreign gross earnings
The tn.movie_budgets dataset has variables such as movie titles, production budgets, and domestic and worldwide gross earnings.



## Methods
This project uses the following Methods

Data Cleaning and Preprocessing: Cleaned and preprocessed the data, addressing missing values, duplicated records, and data type conversions. This is done to prepare the data for analysis

Data Exploration: Performed Exploratory analysis (EDA) and feature engineering to understand and configure the characteristics of the data and identify patterns.

Data Visualization: Visualizating the data contributed immensely to our insights, providing clear and impactful representations of data trends

## Results

During the analysis we observed that genres such as 'Adventure' and 'Sci-Fi' exhibit the highest production budgets. Interestingly, these genres also demonstrate the potential to generate substantial revenue, which positions them as promising choices for Microsoft's movie studio.We also discovered that movies released in the summer and around the holiday season tend to perform better at the box office.

![Most Profitable Genre](highest_grossing.png)

![Distribution of Profit by season](Season_vs_Profits.png)

![Relationship between Budget and Profit](Budget_vs_Profits.png)


Our actionable insights suggest that Microsoft should consider investing in 'Adventure' and 'Sci-Fi' genres particularly during peak release periods for maximum profit. Additionally, partnering with well-established studios or co-producing films with experienced industry players could enhance the chances of success.

![Top Studio performance](Studio_vs_Profit.png)


As a result of our analysis, we recommend that Microsoft focuses on producing high-quality films in the 'Adventure' and 'Sci-Fi' genres. We also suggest exploring collaboration opportunities with successful studios to leverage their industry expertise.



## Conclusion

This analysis leads to these recommendations to help microsoft decide the type of films to create:

Genre selection:Focus on "sci-fi" and "animation" genres for film production.These two genres have had highest worlwide Gross revenue at the box office."sci-fi" genre as shown strong popularity among audience as it received the highest votes.This indicates strong audience preference.

Strategic Timing: Microsoft should strategically time their film releases, aiming for the summer and holiday seasons. This can optimize box office earnings and overall performance.

Combined_Genre Selection: Focus on 'Adventure, Drama, Sci-Fi' genres combination for film production, as this genres have shown strong poplarity ,high rating and high box office performance, indicating significant audience interest.it has been the most successful genre combination at box office currently.

High-Engagement Genres: Invest in a strong social media presence to reach a diverse international audience. Prioritize creating films genres that are apealing  and quality such as "sci-fi" genre.This engages the audience, as movies with a high number of votes tend to perform well at the box office. This approach can lead to increased audience engagement and higher box office returns.

Budget Allocation for Maximum Profit: consider allocating a larger budgets to produce high Quality films in the genres such as Adventure or Sci-fi genres.Genres that had a well production budget for a movie had higher worldwide Gross and profits. 

Collaboration with Studios: Explore collaboration opportunities with successful studios like P/DW and BV studios , as they have demonstrated high total gross revenues. Such partnerships have the potential to enhance profitability.Building strategic partnerships with successful studios can provide opportunities for co-productions and co-distribution can as well increase your audience.


## Next steps

Further analyses could yield additional insights to help microsoft's studio create films:

Better understanding of content themes.This modeling could analyze the most common themes in the specified genres that are apealing to audience.This can be useful in crafting relevant and captivating storylines.

Better Understanding of audience.This modeling can help understand the age distribution,gender distribution and locations of our audience in order to develope marketing strategies to help make higher revenues.
