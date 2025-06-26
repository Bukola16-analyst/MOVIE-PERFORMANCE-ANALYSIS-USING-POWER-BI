INTRODUCTION

This project discovers how movies perform using easy-to-understand visuals created with Power BI. I looked at important details like movie genres, ratings, views, fan base, language, directors, and more.

The goal is to understand what makes a movie successful, what people like to watch, which genres do best, and how different factors (like the director or the language) affect a movie’s popularity. With interactive dashboards, you can easily explore the data, spot trends, and get clear insights that help in making better decisions for future movies.

Whether you’re a movie fan, a data enthusiast, or someone in the film industry, this analysis gives a clear picture of what works in movies and why.

AIM

The aim of this report is to analyze the performance of various movies using Power BI tools in order to identify key trends, patterns, and factors that contribute to a movie’s success across different metrics.

OBJECTIVES

To visualize movie data in an interactive and easy-to-understand format using Power BI.

To analyze the impact of genre, ratings, views, and fan base on movie performance.

To compare how different directors, studios, and languages influence audience reception.

To identify top-performing movies and trends across various platforms.

To generate actionable insights that can support better decision-making in movie production, marketing, and distribution.

Problem Being Addressed

With the growing number of movies released every year, it can be challenging to understand what truly drives a movie’s success. Factors like genre, ratings, language, studio, and viewer engagement all play a role, but without proper analysis, it’s hard to tell which one’s matter most.

This report addresses the need for a better understanding of movie performance by analyzing detailed movie data. The goal is to uncover patterns and insights that can help stakeholders, such as producers, marketers, and streaming platforms to make smarter decisions based on actual viewer preferences and performance trends.

KEY DATASET AND METHODOLOGIES

Key Dataset

Key fields in the dataset are:

· Title — Name of the movie

· Genre — Type/category of the movie (e.g., Action, Drama, Comedy)

· Studio — Production studio or company

· Director — Director of the movie

· Original Language — Language the movie was originally released in

· Likes — Number of likes received

· Watches — Number of times the movie has been watched

· Average Rating — Viewer rating on a scale (e.g., 1 to 5)

· Total Ratings — Total number of rating entries

· Rating Distribution — Breakdown of how many users rated 1-star, 3-star, or 5-star

· Fans — Number of fans or followers for the movie

· Appearances — Possibly how often the movie appears in lists/playlists or on platforms

· Run Time — Duration of the movie in minutes

Methodologies

I used Power Query Editor for the Data Cleaning

Checked for missing or inconsistent values

Ensured consistent letters (e.g., uppercase or lower case)

Ensured correct data types (e.g., numerical, text, dates)

Visualization with Power BI

· Used bar charts, pie charts, tables, and KPI cards to represent key metrics

· Created interactive filters and slicers (by genre, language, director, etc.)

DAX Calculations

· Create New measures (e.g., total likes, total watches)

Insight Generation

· Identified top-performing genres, languages, and studios

· Compared directors’ movie performance

· Highlighted user behavior and rating trends

STORY OF DATA

The Data is a Movie Datasets downloaded from Kaggle.com

Data structure: Each row in the Excel spreadsheet represents a unique id, while each column represents a specific attribute or variables like director, studio, fan, total likes, average rating, etc.

IMPORTANT FEATURES AND THEIR SIGNIFICANCE

Total Likes

Significance: this indicates popularity of a movie among users, this is useful for measuring engagement.

Average rating

Significance: this represent the overall audience satisfaction, this is useful for quality-based comparisons

Total watches:

Significance: This reflects audience reach and viewing frequency, helps identify top performing content

Total Rating

Significance: this measures total number of rating submissions

Run Time

Significance: this helps to see if shorter/longer movies perform better.

Fan Count

Significance: this Measures fan loyalty or deep audience interest. A Strong indicator of long-term popularity.

Studio:

Significance: this allows production house comparison; this is useful for strategic insights across production companies

Genres

Significance: This is useful for analyzing preferences by content type (Action vs Comedy)

Director

Significance: Facilitates analysis of director-specific success

Original Language

Significance: useful for audience targeting, and multilingual performance comparison

Title & Description: Identifies and describe each movie

Release Year: Allows trend analysis over time, for example, are movies getting better rated or more watched over years.

Data Cleaning

I used Power Query Editor for the Data Cleaning

Checked for missing or inconsistent values

Ensured consistent letters (e.g., uppercase or lower case)

Ensured correct data types (e.g., numerical, text, dates)

Data splitting

The data were split into two categories

Independent and dependent variables or value

PRE- ANALYSIS BOARD

Project split

Independent variables or values from the dataset includes Genres, director, original language, film title, studio, description.

Dependent values or variables from the datasets are average rating, likes, fans, runtime, total rating, watches.

DAX measures

Total watches: SUM (movie dataset(watches)

Total likes=sum(movie datasets(likes))

Potential Analysis

· Top performing Genre by total watches Film Title by total watches and average rating (most watched film title by average rating)

· Top film Title with total likes

· Film title with highest Run time

· Genre with Highest Fans

· Highest Liked Director (Director with total likes)

· Top Language by Total likes

Key KPI

Cards

Total Likes

Top like Movie

Potential Insights

· Top performing Genre by total watches, the objective is to know the top performing genre by total watches

· Film Title by total watches and average rating (most watched film title by average rating),

· Top film Title with total likes the objective is to know which genre get the most fans

· Film title with highest Run time The Objective is to know How Movie length affects engagement

· Genre with Highest Fans the objective is to the

Highest Liked Director The objective is to evaluate performance of production sources.

· Top Language by Total likes The Objective is to analyze movie reception based on language, identify which language movie the audience prefer most.

INANALYSIS BOARD

In- analysis Observation

· From the analysis of the Top performing Genre by total watches, the top performing genre are Drama with total watches of 85M, followed by comedy 43M, Comedy Drama 34M, Drama, Comedy 27M, Comedy, Romance28M, and the last top 6 is Drama Romance 24M.

· Film Title by total watches and average rating, the Top movie with total watches and average rating are Barbie with total watches of 5195503 and average rating of 3.78, followed by fight club total watches of 5059722 and average rating of 4.27, Parasite ,5018694 and average rating of 6.95, Dark knight 4488171 and average rating of 4.48, Trauma Show 4382819, and average rating of 4.22, pulp fiction, 4386659 and average rating of 4.25

· Film title with highest Run time ,Berlin Alexander plat has the highest runtime of 907minues and total watches of 9689, followed by the stand ,run time of 876minutes and total watches of 33970, out 1 ,run time of 743 with total watches of 7217, cleopatra ,run time of 702minutes with watches of 263344, Claudius runtime of 669, watches of 5509,Brideshead revisited runtime of 659 watches of 5214, Hercules runtime of 616, watches of 1427308, planet earth , runtime of 612 watches of 121575, and your honor runtime of 600, watches of 16390.

· Genre with Highest Fans, the top genre with highest engagement/fans are Drama 1746246K, Romance, Drama 491971k, Drama Romance 482084K, Drama Romance 482084K, Comedy, Drama 398102k, Drama Comedy 387717K. and Drama Crime 376855K.

· Highest Liked Director, the top 5 director with highest total likes are Christopher Nolan with total likes of 10.6M, followed by Quentin Tarantino 8.8M, David Fincher 7.2M, Steven Spielberg 6.4M, and Hayao Miyazaki 5.8M.

· Top Language by Total likes, the original language with the highest likes is English with percentage of 93.63%, followed by Japanese 3.14%, French 1.49%. Korean 1.25%

· The film title with highest likes is parasite with total likes of 2,731280M, Followed by Interstellar ,2,417030M, Fight club ,2,325525M, Spider man: into the spider verse ,2,218461M, Barbie 2,140,382M, The Dark knight 1,986315M

In analysis Insights

· Top performing Genre by total watches, the drama genre has the highest number of total watches with 85M Watches, outperforming other genres by a significant margin

· Film Title by total watches and average rating (most watched film title by average rating), Parasite stands out with the highest average rating of 6.95 and over 5.0M total watches.

· Top film Title with total likes, Parasite is the most liked film with 2.7M likes this indicates extremely high viewer satisfaction.

· Film title with highest Run time and total watches, The Hercules, run time of 616minutes and still has over 1.4M watches this proves that long form content can still attract high viewership even though the top film Berlin Alexander plat with highest run time of 907minutes has few watches of 9689K watches.

· Genre with Highest Fans, Drama has the highest fan base with 1,7462,46M fans this shows strong loyalty and repeat engagement.

· Highest Liked Director, Christopher Nolan is the highest liked director with 10.6M total likes across all his films, this means audience sentiment and engagement are high for his works/movie.

· Top Language by Total likes, English films dominates in total likes with 93.63%



POST ANALYTICS

FINAL OBSERVATION AND RECOMMENDATION

Final Observation

· From the analysis of the Top performing Genre by total watches, the top performing genre are Drama with total watches of 85M, followed by comedy 43M, Comedy Drama 34M, Drama, Comedy 27M, Comedy, Romance28M, and the last top 6 is Drama Romance 24M.

· Film Title by total watches and average rating, the Top movie with total watches and average rating are Barbie with total watches of 5195503 and average rating of 3.78, followed by fight club total watches of 5059722 and average rating of 4.27, Parasite ,5018694 and average rating of 6.95, Dark knight 4488171 and average rating of 4.48, Trauma Show 4382819, and average rating of 4.22, pulp fiction, 4386659 and average rating of 4.25

· Film title with highest Run time ,Berlin Alexander plat has the highest runtime of 907minues and total watches of 9689, followed by the stand ,run time of 876minutes and total watches of 33970, out 1 ,run time of 743 with total watches of 7217, cleopatra ,run time of 702minutes with watches of 263344, Claudius runtime of 669, watches of 5509,Brideshead revisited runtime of 659 watches of 5214, Hercules runtime of 616, watches of 1427308, planet earth , runtime of 612 watches of 121575, and your honor runtime of 600, watches of 16390.

· Genre with Highest Fans, the top genre with highest engagement/fans are Drama 1746246K, Romance, Drama 491971k, Drama Romance 482084K, Drama Romance 482084K, Comedy, Drama 398102k, Drama Comedy 387717K. and Drama Crime 376855K.

· Highest Liked Director, the top 5 director with highest total likes are Christopher Nolan with total likes of 10.6M, followed by Quentin Tarantino 8.8M, David Fincher 7.2M, Steven Spielberg 6.4M, and Hayao Miyazaki 5.8M.

· Top Language by Total likes, the original language with the highest likes is English with percentage of 93.63%, followed by Japanese 3.14%, French 1.49%. Korean 1.25%

· The film title with highest likes is parasite with total likes of 2,731280M, Followed by Interstellar ,2,417030M, Fight club ,2,325525M, Spider man: into the spider verse ,2,218461M, Barbie 2,140,382M, The Dark knight 1,986315M

Final Recommendation

· Top performing Genre by total watches, I Recommend will prioritize licensing or producing more drama films, the best genre, we can also increase marketing spend for new releases in this genre, feature the best genre prominently in dashboards and front pages to attract more audiences.

· Film Title by total watches and average rating (most watched film title by average rating), Parasite stands out with the highest average rating of 6.95 and over 5.0M total watches. i recommend we feature this film prominently in the recommendation engines, we can use it as a bench mark to identify traits of successful content, and also consider creating related content to boost or increase watches and ratings

· Top film Title with total likes, Parasite is the most liked film with 2.7M likes this indicates extremely high viewer satisfaction, I Recommend we use audience feedback to surface similar films, also highlights user testimonials or reviews in promotional campaigns, we can also push this film to new users as a highly liked recommendation movie to attract them.

· Film title with highest Run time and total watches , The Hercules ,run time of 616minutes and still has over 1.4M watches this proves that long form content can still attract high viewership even though the top film Berlin Alexander plat with highest run time of 907minutes has few watches of 9689K watches, I recommend we don’t shy away from recommending long form films , they can also perform well if content is strong, also consider promoting these during weekends or holidays when users have more time to spare, and track completion rates to understand viewing habits .

· Genre with Highest Fans, Drama has the highest fan base with 1,7462,46M fans this shows strong loyalty and repeat engagement, I recommend we launch fan-based campaigns or reward programs, also encourage user rated content like reviews, we can also build watchlists to keep engagement high.

· Highest Liked Director, Christopher Nolan is the highest liked director with 10.6M total likes across all his films, this means audience sentiment and engagement are high for his works/movie, i recommend we promote existing movies by this director spotlight campaigns and consider exclusive interviews, behind the scenes content collections, and also track new releases or partnerships involving this director.

· Top Language by Total likes, English films dominates in total likes with 93.63%, I Recommend we expand promotion of multilingual films with strong like rates, also includes subtitles or labeled versions to broaden audience reach, consider language specific recommendations on the home screen.

CONCLUSION

This analysis of the movie dataset in Power BI offers valuable insights into what kinds of movies people like, watch, and follow. Among all the films, Parasite stands out as the most liked movie with 3 million likes, showing that international films can compete strongly with big-budget Hollywood movies. While blockbusters like Fight Club, Interstellar, Spider-Man: Into the Spider-Verse, and The Dark Knight also received around 2 million likes each, Parasite had the highest average rating overall, this shows that popularity and quality don’t always go hand in hand.

The data also shows that English-language movies dominate, accounting for over 93% of total likes. Other languages like Japanese, French, Korean, and Spanish make up a very small share. This may be due to wider availability or larger audiences for English-language content.

Interestingly, movie runtime doesn’t seem to play a big role in how much people like or watch a film. Even though longer films like Interstellar and Planet Earth are on the list, there’s no strong link between runtime and popularity.

There is also a noticeable difference between movies that are most watched and those that are highest rated. For example, Barbie, Joker, and Interstellar were watched the most, but Parasite received the highest ratings. This shows that some movies are widely watched but not necessarily well loved, while others earn strong praise from a smaller group of viewers.

When it comes to fans, movies in the Drama category, especially those mixed with Romance or Comedy, attract the most followers. These genres seem to build stronger emotional connections with audiences, which helps grow loyal fan bases.

Among directors, Christopher Nolan received the most likes (10.6 million), followed by Quentin Tarantino, David Fincher, Steven Spielberg, and Hayao Miyazaki. This highlights how certain directors consistently create movies that people really connect with.

Lastly, genres that mix Drama with other elements like Comedy or Romance perform best when it comes to total watches, some with over 85 million views. This suggests that audiences enjoy movies that balance emotion with entertainment. With a total of 437 million likes across all movies in the dataset, it’s clear there is strong audience engagement, offering plenty of useful insights for content creators, studios, and marketing teams moving forward.
