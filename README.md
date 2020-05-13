# Sentiment-Analysis-in-R

**Objective:**

To build a sentiment analysis model which will allow us to categorize words based on their sentiments, that is whether they are positive, negative and also the magnitude of it.
Before we start with our R project, Let's understand Sentiment Analysis in detail.

**Sentiment Analysis:**

Sentiment Analysis is a process of extracting opinions that have different polarities.

By polarities, we mean positive, negative or neutral. It is also known as opinion mining and polarity detection.

With the help of sentiment analysis, you can find out the nature of opinion that is reflected in documents, websites, social media feed, etc.

Sentiment Analysis is a type of classification where the data is classified into different classes.

These classes can be binary in nature (positive or negative) or, they can have multiple classes (happy, sad, angry, etc.)


## SUMMARY

In this project, We went through our project of sentiment analysis in R. We learnt about the concept of sentiment analysis and implemented it over the dataset of Jane Austen’s books. We were able to delineate it through various visualizations after we performed data wrangling on our data. We used a lexical analyzer – ‘bing’ in this instance of our project. Furthermore, We also represented the sentiment score through a plot and also made a visual report of wordcloud.

## EXPLANATION OF COMPLETE PROJECT:-

### A.Packages Involved:

1.dplyr is a grammar of data manipulation, providing a consistent set of verbs that help you solve the most common data manipulation challenges:

    mutate() adds new variables that are functions of existing variables
    select() picks variables based on their names.
    filter() picks cases based on their values.
    summarise() reduces multiple values down to a single summary.
    arrange() changes the ordering of the rows.
    
2.'mnormt'- The Multivariate Normal and t Distributions.

3.SnowballC - Snowball Stemmers Based on the C 'libstemmer' UTF-8 Library.

4.broom - takes the messy output of built-in functions in R, such as lm, nls, or t.test, and turns them into tidy data frames.

5.tokenizers - Fast, Consistent Tokenization of Natural Language Text.

6.janeaustenr - provides access to the full texts of Jane Austen’s 6 completed, published novels.

7.ggplot2 -  Create Elegant Data Visualisations Using the Grammar of Graphics.

8.wordcloud - Functionality to create pretty word clouds, visualize differences and similarity between documents, and avoid over-plotting in scatter plots with text.
