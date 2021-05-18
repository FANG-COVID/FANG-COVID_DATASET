# FANG-COVID_DATASET

This repository contains the FANG-COVID dataset from "FANG-COVID: A New Large-Scale Benchmark Dataset for Fake News Detection in German".

Its three folders contain the following data:

- not_preprocessed: the whole FANG-COVID dataset containing all textual content from news articles
- preprocessed: the whole FANG-COVID dataset with preprocessed news articles that served as input for CoCoGen and our classifier (we removed repeating textual patterns so our model would not recognize news articles based on publisher-specific obvious features)
- training_data (whole_df): the FANG-COVID dataset as well as its corresponding CoCoGen features that served as input to our classifiers
