# TidyTuesday Project Proposal

For the TidyTuesday challenge, I have chosen the Spotify 2020 dataset. The dataset contains information about the most streamed songs on Spotify in the year 2020, including variables such as track name, artist name, popularity, danceability, energy, and more.

The goal of this project was to gain a deeper understanding of the dataset and uncover interesting insights about the characteristics of popular songs on Spotify. Specifically, I plan to focus on exploring the relationship between various variables and their impact on the popularity of songs.

## Step 2: Exploratory Data Analysis

### Variable Exploration

In this step, I will explore the individual variables in the dataset and examine their distributions, summary statistics, and any notable patterns or trends. This exploration will provide insights into the characteristics of the songs and help identify potential variables of interest for further analysis. Key variables include Track Album Release Date, Song Popularity, Valence, Tempo, Danceability, Liveliness and Instrumentalness.

### Exploring Relationships between Variables

After gaining an understanding of the individual variables, we investigate the relationships between them. I will examine correlations, conduct visual analyses, and perform statistical tests to determine if there are any significant associations between variables. This exploration will help identify key factors that contribute to the popularity of songs on Spotify. The key relationships explored are Year of Album Release vs Popularity Score, Tempo & Danceability, Tempo and Valence, Valence & Danceability and Liveliness & Instrumentalness.

### Confidence Interval Estimations

To quantify the uncertainty associated with our findings, I will compute confidence intervals for relevant estimates. These intervals will provide a range of plausible values for population parameters and help us assess the precision and reliability of our analyses. By interpreting the confidence intervals, we can make more informed conclusions about the relationships and patterns observed in the data. The tempo mean confidence interval and track popularity mean confidence interval will be based on the population, valence variance confidence interval will be based on the population. The difference between the two means will be determined via the confidence interval that depends on instrumentalness and liveliness. The ratio between the two variances will be determined via the confidence interval that depends on valence and danceability.

## Step 3: Hypothesis Testing

In this step, I will develop a research question based on the findings of the exploratory study. The null and alternative hypotheses for testing the association between variables will then be specified.

I will state and check the assumptions regarding the statistical models used to assure the validity of the hypothesis testing. Assumptions like as independence, normalcy, and equal variances will be included.

Following that, I'll compute the observed test statistic and its accompanying p-value. The test statistic quantifies the strength of evidence against the null hypothesis, whereas the p-value indicates the likelihood of detecting such strong evidence by chance alone.

Based on the p-value and a significance level of 0.05, I will make a decision whether to reject the null hypothesis or fail to reject it. This decision will depend on whether the observed test statistic falls in the critical region defined by the significance level.

I'll wrap up the hypothesis testing by summarising the results, going over the results' implications, and pointing out any shortcomings or potential new research fields.

These are the actions I intend to take in order to acquire useful insights into the Spotify 2020 dataset and advance our knowledge of the elements that influence the success of songs on the platform.
