This folder consists of the final group project submitted as a part of Platforms for Big Data Processing in UMBC.

**Introduction to Steam Review Analysis Project**

**Objective:**
The Steam Review Analysis project aims to explore and derive insights from a large dataset containing reviews of games on the Steam platform. Leveraging PySpark for data processing, Pandas for exploratory data analysis (EDA), and visualization libraries like Matplotlib and Seaborn, the project focuses on several key categories to uncover patterns, trends, and valuable information from the vast amount of Steam review data.

**Data Source:**
The dataset, sourced from Kaggle ([Steam Reviews 2021](https://www.kaggle.com/datasets/najzeko/steam-reviews-2021)), comprises approximately 8 GB of data with 17 million rows and 23 columns. The dataset provides detailed information about individual game reviews, including attributes such as the review text, author details, game information, and more.

**Project Components:**

1. **Games Analysis:**
   - Explore the distribution of reviews among different games.
   - Identify the most reviewed and highest-rated games.
   - Analyze the trends in game reviews over time.

2. **Language Analysis:**
   - Examine the distribution of reviews across different languages.
   - Explore the sentiment of reviews in different languages.
   - Identify popular languages among Steam users.

3. **Time Analysis:**
   - Investigate how the volume of reviews changes over time.
   - Analyze temporal patterns in sentiment.
   - Identify peak times for reviews.

4. **Author Analysis:**
   - Explore characteristics of authors, such as the number of games owned and reviewed.
   - Identify prolific reviewers and their reviewing behavior.
   - Analyze playtime patterns of reviewers.

5. **Game Recommendation using ALS model:**
   - Alternating Least Squares matrix factorization model is implemented to recommend games to players who plays a game.
   - It is a popular collaborative filtering algorithm.
   - The model is trained using the author indices, app indices, and ratings.
   - We use the trained model to generate recommendations for all gamers.

**Technology Stack:**
- **Spark SQL:** Used for extraction, processing, and analysis of the data set.
- **Spark MLLib:** Uses the ALS collaborative filtering algorithm for recommending games.
- **Pandas:** Employed for exploratory data analysis and manipulation.
- **Matplotlib and Seaborn:** Utilized for data visualization to derive meaningful insights.
- **Hadoop Distributed File System (HDFS):** Chosen for storing the extensive dataset.

**References:**
The project drew inspiration and guidance from existing Kaggle kernels, particularly [Steam Reviews](https://www.kaggle.com/code/gonzafrancoandres/steam-reviews) and [Review Analysis by PySpark](https://www.kaggle.com/code/iplori/review-analysis-by-pyspark), for building upon best practices in working with Steam review data.

Through comprehensive analysis across these categories, the Steam Review Analysis project seeks to provide valuable insights for game developers, platform administrators, and researchers interested in understanding user sentiments and behaviors within the Steam gaming community.
