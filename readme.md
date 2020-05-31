# Wrangle and Analyze WeRateDogs Data
## by Shweta Negi


## Introduction

In this project WeRateDogs Twitter data is wrangled to create interesting and trustworthy analyses and visualizations. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. Using Python and its libraries, data is gathered from a variety of sources and in a variety of formats, then it is assessed for its quality and tidiness, then neccessary cleaning is done.

## Dataset

Data is gathered from following sources:

1. Enhanced Twitter Archive: The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything.
2. Image Predictions File: After running every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs. The results are stored in a table full of image predictions. This data can be gathered from Udacity's web page
3. Additional Data via the Twitter API: In Twitter archives data retweet count and favorite count are two of the notable column omissions. Fortunately, this additional data can be gathered by anyone from Twitter's API.

## Important points to focus while exploring data

1. Which is the most common dog_stage that people own?
2. What is the relation between favorite_count and retweet_count?
3. What is the most common rating_numerator for a dog?
4. What are the 10 most frequent predicted dog breeds?



## Key Insights from the Analysis

> 1. Most of the dogs are not having any stage information still Pupper is the most common dog stage among the four. Very less people own floofer and puppo.
2.  There is a positive correlation between favorite_count and retweet_count.
3. Top 10 frequent dog breeds are golden retriever, labrador retriever, pembroke, chihuahua, pug, chow, samoyed, pomeranian, toy poodle, malamute. Among them golden retriever is the most common.
4. The rating_numerator gradually increases upto 9 and the most common rating for a dog is 12, 10, and 11 after that comes 13. Though they are less but some very high numerator ratings also exist.
