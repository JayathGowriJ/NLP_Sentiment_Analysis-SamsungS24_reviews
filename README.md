# Project : Samsung Galaxy S24 Ultra 5G Review Analysis
![image.png](attachment:image.png)

## Product: 
    Samsung Galaxy S24 Ultra 5G (Titanium Violet, 256 GB) with 12 GB RAM

## Objective: 
    To analyze customer reviews of the Samsung Galaxy S24 Ultra 5G from Flipkart, focusing on sentiment analysis, word frequency, and topic modeling to gain insights into customer opinions and product attributes.

## Steps Taken:

### Data Collection:

    Utilized Selenium for web scraping to gather reviews from the Flipkart product page and saved the data into a CSV file.

### Data Cleaning:

    Checked the data for null values and duplicates.
    Applied common text preprocessing techniques:
        Stopword removal
        Removal of links and punctuations
        Lowercasing
        Lemmatization
### Text Analysis:

#### Word Frequency Analysis:
    Generated a word cloud to visualize the most frequently occurring words in the reviews.
    
#### Review Length Analysis:
    Analyzed the distribution of review lengths.
    
#### Distribution of Product Ratings:
    Plotted the distribution of ratings to visualize the frequency of each star rating.
    
#### Sentiment Analysis:
    Used TextBlob to analyze the sentiment of reviews.
    Findings:
    * 85.98% of reviews are rated 5 stars.
    * 12.15% of reviews are rated 4 stars.
    * 1.87% of reviews are rated 3 stars.
    * 89.72% of reviews show positive sentiment.
    * 6.54% of reviews are neutral.
    * 3.74% of reviews show negative sentiment.
    * The sentiment analysis is consistent with the manual ratings given.

#### Topic Modeling:

    Applied Latent Dirichlet Allocation (LDA) to identify prevalent topics in the reviews.
###### Topics Identified:

    Topic 1: Focuses on general positive aspects of the product, with words like "great," "superb," "excellent," and "good" indicating overall satisfaction and high performance.
    
    Topic 2: Highlights specific features and attributes of the phone, with words like "battery," "display," "camera," and "awesome" indicating praise for particular features.


## Results:
    Ratings: Majority of the reviews are positive, with a high percentage of 5-star ratings.
    
    Frequent Words: Common terms include "phone," "camera," "best," and "good."
    
    Review Length: Most comments are concise, with a word count of less than 10 words, and three-word reviews being most common.
    
    Sentiment: The sentiment analysis shows that the majority of reviews are positive, aligning well with the high rating distribution.
    
    Topics: Two main topics were identified, reflecting general satisfaction and specific features.

This analysis provides valuable insights into the actual customer perceptions and highlights key areas of satisfaction and feature appreciation for the Samsung Galaxy S24 Ultra 5G.
