## Table of Contents
- [Chapter 1 - Generating Dataset](#chapter-1---generating-dataset)
- [Chapter 2 - Text Processing](#chapter-2---text-processing)
- [Chapter 3 - Applying Sentiment and Candidate Scores](#chapter-3---applying-sentiment-and-candidate-scores)
- [Chapter 4 - Obtaining the Analysis Ready CSV](#chapter-4---obtaining-the-analysis-ready-csv)

## Chapter 1 - Generating Dataset

In this chapter, we utilized the YouTube API to generate a dataset for the analysis we will be conducting. We first identified a selection of YouTube channels that were to be analyzed. Once we had the list, we retrieved the statistics for both the channels and their respective videos using the YouTube API. Subsequently, we collected the channel names, titles of videos published since February, comments on the selected videos, and the corresponding publish dates of the comments in order to construct the dataset. Upon creating the dataset, we proceeded to save it as a CSV file for each individual channel.

## Chapter 2 - Text Processing

In this chapter, comments that have been gathered are going to be put through some processes. By using a model, we are going to get their sentiment score and determine which presidential candidate they are related to. Google Translator is used since we could not find any Turkish sentiment analyzer model.

## Chapter 3 - Applying Sentiment and Candidate Scores

Initially, dividing our dataframe into chunks was not in our plans, but due to the sentiment model taking more time than expected, we ended up using the chunk technique. 

## Chapter 4 - Obtaining the Analysis Ready CSV

We arranged data types and applied candidate scores function to the data set we have. Finally, after getting done with all the process we wrote our final dataframe to our a CSV file.