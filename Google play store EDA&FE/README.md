## EDA And Feature Engineering Of Google Play Store Dataset

1) Problem statement.
Today, 1.85 million different apps are available for users to download. Android users have even more from which to choose, with 2.56 million available through the Google Play Store. These apps have come to play a huge role in the way we live our lives today. Our Objective is to find the Most Popular Category, find the App with largest number of installs , the App with largest size etc.
2) Data Collection.

The data consists of 20 column and 10841 rows.





### Steps We Are Going to Follow
1. Data Clearning
2. Exploratory Data Analysis
3. Featur eEngineering


#  summary

* App Performance & Engagement
Rating: The distribution is left-skewed, with a heavy concentration of apps rated between 4.0 and 4.5. High ratings are the norm, while very low ratings (below 3.0) are rare.

* Reviews & Installs: Both show a massive right skew. Most apps have a relatively small number of reviews and installs, while a tiny handful of "superstar" apps reach the millions (or billions for installs), creating a "long tail" effect.

* App Characteristics
Size: Most apps are relatively small (under 20,000 units, likely KB), but there is a steady decline as size increases, with very few apps reaching the 100,000 mark.

* Price: This graph shows that the vast majority of apps are free or very low-cost. There is a negligible count for apps priced toward the $400 mark, suggesting those are extreme outliers.

* Temporal Trends (Update Recency)
Last Updated / Year: There is a significant spike in 2017 and 2018. This indicates that the dataset contains many currently maintained apps, or that the data was scraped/collected during that period.

* Month: Updates peak mid-year (around July), though there is a decent distribution across all months.

* Day: Updates are fairly evenly distributed throughout the month, with a slight peak at the very beginning of the month (Day 1-3).

* Dominant Categories: The Family category is the clear leader by a significant margin, with a count approaching 2,000. It is followed by Game (approx. 1,150) and Tools (approx. 850).

* The "Middle Class": There is a sharp drop-off after the top three. Categories like Medical, Business, and Productivity hover around the 400–500 range.

* The Long Tail: The frequency levels off as you move toward the right of the chart. The bottom five categories shown—including Social, Shopping, and Dating—all fall below the 300 mark, showing much less variance between them compared to the top of the list.

### 
1. Which Category has largest number of installations??
2. What are the Top 5 most installed Apps in Each popular Categories ??
3. How many apps are there on Google Play Store which get 5 ratings??

