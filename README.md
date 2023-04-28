# MIST-4610_GP2

Movie Industry
Group Name and Members
Group 21482_ 6

Aaron Fritchley

Mason Layfield

Alexandra Shalikashvili

Simran Singh

Ashley Skaggs

Dataset Information
The dataset ‘Movie Industry’ was obtained from the website Kaggle and contains 6820 movies with 15 attributes. The creator’s purpose of the dataset was to evaluate if the movie industry is dying out at a time when streaming giants like Netflix have become more popular. The dataset contains information about movies released over a span of four decades. The main content of the dataset includes information related to each movie’s name, budget, company, country, director, genre, gross revenue, rating, release date, runtime, score, votes, star, writer, and year of release. The purpose of the dataset is to show movie revenue and analyze the many factors that impact it. Each movie has the following attributes:

Column Name	Data Type
Budget	Decimal
Company (production company)	String
Country	String
Director	String
Genre	String
Gross	Decimal
Name	String
Rating (R, PG, etc.)	String
Released Date	String
Runtime	Decimal
Score	Decimal
Votes	Decimal
Star	String
Writer	String
Year	Decimal (changed to Date)
Questions
Question 1
For action comedy and horror movies, what is the correlation between runtime and the movie’s score from 2000 to 2009 compared to 2010 to 2019?

Explanation: This question is culturally significant in detailing how attention spans have changed over the last decade across different genres. Each movie has a designated run time and also was assigned a score out of 10 from IMDB. This information can be cross-referenced when projecting future optimal runtimes

Question 2
How many movies have the countries with the highest average movie industry net income produced from 2010-2020?

Explanation: This question is economically significant in showing what countries produced the most movies compared to their net income. This could also show which countries have the most net income per movie but produced few movies compared to countries that produced the most movies but also have high net income. We were able to create a calculated field from each movie's budget and gross revenue to build a heat map showing the highest average net income by country. We then used this information to select the top 5 highest net-income nations to construct a bar graph showcasing the number of movies produced by that countries.

Manipulations to Data
Some of the values for the budget attribute were null due to the data not being available for those movies. We decided to remove these values via a filter on the whole dataset so it would not interfere with our visualizations. We also decided to create a calculated field called net by subtracting the budget from the gross for each movie. This was done to show how much each movie made so we could then create a heat map to compare how much each country made in net income from the movie industry on average.

Analysis and Results
Q1: As you can see in our first graphics, we compare the runtime and scores of different genres of films in the 2000’s and 2010’s. As time goes on, the line of regression showcases a positive correlation between total runtime and score in each genre; with action movies having the greatest increase in runtime in both decades, comedies having the lowest increase in runtime in the 2010s, and horror having the lowest increase in runtime in the 2000s. Therefor the graphs that showed the lowest positive correlation are comedies in the 2010s and horror in the 2000s.

Screenshot 2023-04-28 at 4 37 14 PM

Q2: In our second graphics, we use a geographical map to showcase the average net income alongside two bar graphs: one showing the average net income again and the other showing the number of movies produced by the countries with the top 5 average movie industry net income. Using these different graphics we can infer that the net income factor does not necessarily affect the production of more movies, and instead could be more of a cultural variable, because of the United States being an outlying leader of movie production despite not having the greatest average net income.

Screenshot 2023-04-28 at 4 38 15 PM
