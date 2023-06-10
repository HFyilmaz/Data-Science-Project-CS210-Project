# data_sources
The **data_sources folder** contains the dataset that we created, cleared, and processed for our project.

## Table of Contents
- [raw_dataset](#raw_dataset)
- [reduced_dataset2K](#reduced-dataset2K)
- [chunked_data](#chunked_data)
- [uncleaned_dataset](#uncleaned_dataset)
- [analysis_ready_dataset](#analysis_ready_dataset)


## raw_dataset
We obtained the dataset using the YouTube API. This dataset includes information such as channelName, video_title, comments, and publishDate of each comment. The original, unprocessed version of this dataset is stored in the raw_dataset folder.

## reduced_dataset2K
In order to facilitate the sentiment analysis process, we randomly selected 2000 comments for each YouTube channel in our list. These randomly chosen comments can be found in the reduced_dataset2K folder. By reducing the dataset, we made it more manageable for sentiment analysis. Otherwise, processing the entire dataset would have been impractical.

## chunked_data
For the third step, we performed sentiment analysis on the dataset. In the chunked_data folder, you will find CSV files that contain the comments, with their respective sentiment scores attached as a new column in each row.

## uncleaned_dataset
The fourth step involved merging the comments that underwent sentiment analysis and cleaning the dataset. This process was carried out on the file stored in the uncleaned_dataset folder.

## analysis_ready_dataset
In the final step, we calculated scores for politicians and prepared the dataset for the analysis phase. The finalized dataset, ready for analysis, can be found in the analysis_ready_dataset folder.