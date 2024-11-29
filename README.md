# Amazon-TV-Content-Analysis
This analysis utilizes the [Amazon Prime Video Movies and TV Shows dataset](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows) available on [Kaggle](https://www.kaggle.com/).


# Problem Statement:

This analysis aims to explore Amazon's movie catalog and uncover valuable insights that can guide decision-making and drive business improvements. The problem I aim to solve was understanding patterns in Amazon's movie/TV shows offerings, such as how different movie genres perform across countries, trends in ratings, and exploring factors that impact the popularity of content. With over 200 million subscribers globally, Amazon Prime can leverage these insights to improve personalized recommendations and refine its content offerings, ensuring that users are presented with the most relevant movies and shows.

# Key Question:

The core questions I aimed to answer through this analysis were:

1.	Whats the distribution of movies and TV shows across different countries in the dataset.
   
2.	What are the most common genres of movies available on Amazon?
	
3.	How do movie ratings vary across shows?
	
4.	What trends can be observed in the release years of movies and TV shows and how do they relate to genre and rating?
	
# Data Overview: 

Amazon Prime is another one of the most popular media and video streaming platforms. They have close to 10000 movies or tv shows available on their platform, they have over 200M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Amazon Prime, along with details such as - cast, directors, ratings, release year, duration, etc.

**Tools & Dataset:**  

•	Microsoft Excel - For cleaning the data
• Power BI -  For visualization.



# Data analysis:

The analysis process involved several key steps to explore the dataset in depth:

**Data Cleaning and Preparation:**
   
The dataset required significant data cleaning to ensure consistency . I used “Sort and Filter” on Excel to find out missing data.  A large portion of the data had missing or incomplete values across multiple columns. Specifically, 8,996 out of 9,668 entries were missing **country** data, and 1,233 entries had missing or blank **cast** information, with 35 entries containing "1" and 1 entry containing "1,2,3." . For **director** column, 2,082 entries were missing, with 17 entries containing "1," 1 entry listed as "20th century fox," 2 entries as "20th_century_fox," and 1 entry as "9 Story Entertainment." Finally, 337 entries had missing **ratings**. 
To ensure consistency, all of these missing or erroneous values were replaced with the placeholder "Unknown" or "Unrated," making the dataset more reliable and ready for further analysis.

<img width="428" alt="image" src="https://github.com/user-attachments/assets/8a424f18-42e3-4184-8db8-e5e7a3d343db">

I saved the cleaned dataset for further analysis.

# Data Visualization:
   
I imported the cleaned dataset into Power BI. 	I made sure that the data was structured correctly by converting categorical fields like type, rating, and country into dimensions that could be grouped.

![image](https://github.com/user-attachments/assets/3850f3a6-0a9f-4712-846e-76f80c5df2d5)


I created a daashboard with following visualizations in Power BI to answer the core business questions:

•	Pie Chart to display the distribution of movies and TV shows types.

•	Heatmaps to highlight the relationship between shows/movies in different countries.

•	Area Chart to show trends in movie and shows releases over the years.

•	Bar charts  to list top genre and rating by total shows

![image](https://github.com/user-attachments/assets/d4a70cd7-f73c-456c-b472-0fee6ae06e45)


# Key Insight:

The analysis revealed the following key insights:

•	Popular Genres: Certain genres like Action, Comedy, and Drama dominate Amazon's movie catalog, while genres like Documentary and Horror appear less frequently.
	
•	Rating Trends: Higher ratings tend to be associated with movies that have a longer duration, though some shorter films with strong storylines also received high ratings.
	
•	Country Insights: The U.S. and India are leading in the number of movies available on Amazon, while other regions like Europe or Canada have relatively fewer offerings.
	
•	Genre Influence: Genres like Comedy and Drama, tend to receive higher ratings and more viewership.
   

# Recommendations:

Based on the analysis, the following recommendations can be made:

•	Focus on Expanding less represented genres: Given that genres like Documentary are underrepresented on Amazon, there is an opportunity to diversify the catalog.

•	Regional content expansion: With the U.S. and India dominating the catalog, Amazon could consider expanding its offerings in underrepresented regions like Europe or Canada.

•	Capitalize on popular genres for better engagement: Comedy and Drama genres receive higher ratings and viewership. Amazon could capitalize on this trend by investing in more original content within these genres


Challenges Faced:
Several challenges arose during the analysis:
1.	Data Quality: Missing or incomplete data for certain columns required extra time for cleaning and handling.
2.	Data Granularity: The dataset lacked certain granular details (viewing history) that would have provided deeper insights into customer preferences.


