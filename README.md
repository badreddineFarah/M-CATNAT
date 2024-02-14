# M-CATNAT  

This repository contains a multimodal tweet annotation dataset aimed at enhancing disaster response efforts and social media analysis. Below is a breakdown of the files included in this repository:

## Files

### 1. `annotations.csv`

This CSV file serves as the main dataset, containing annotations for each tweet instance. Each row represents a unique tweet, with the following columns:

- **tweet_id**: The unique identifier for the tweet.
- **text_label**: The annotation label for the tweet text.
- **image_label**: The annotation label for the tweet image.
- **multimodal_label**: The annotation label for the the multimodal instance  .
- 
- **notes**:

In cases where a tweet contains multiple images, the tweet IDs are followed by numbers separated by underscores. For instance, `tweet_id_1` represents the first image in the tweet URLs list obtained from the Twitter API.

### 2. `annotation_guide_v2.html`

This document presents the second version of our annotation guide. It offers instructions and examples to resolve any potential disagreements among annotators, ensuring consistency in labeling the dataset.

## Dataset Description

The dataset consists of multimodal tweets related to natural disasters, sourced from Twitter. Each tweet is annotated based on predefined criteria outlined in the annotation guide. 



