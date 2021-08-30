# Overview
This repository contains the annotated dataset, the unigrams, bigrams and trigrams referenced in the paper **"COVID-19 Vaccine Hesitancy in the Month Following the Start of the Vaccination Process"** submitted to **International Journal of Environmental Research and Public Health**.

The tweets have been collected between **December 8, 2020** and **January 7, 2021** as described in our paper. The aim of the paper is to analyze the dynamics of the public opinion on Twitter in the first month after the start of the vaccination process in UK (on December 8, 2020) with a focus on the COVID-19 vaccine hesitancy messages.

> Note: The tweets have been minimally pre-processed before extracting the n-grams by removing stop words and duplicated white spaces.

Repository structure:
- dataset: contains a balanced dataset with 4341 tweets annotated in the categories "against" (0), "neutral" (1) and "in favor" (2);
- n-grams: daily unigrams, bigrams and trigrams extracted from the dataset containing all the tweets, sorted by the number of appearances;

# Usage
In accordance with the Twitter policy, in the annotated dataset, only the tweet ids have been provided. The tweets can be hydrated using a tool such as Twarc (https://github.com/DocNow/twarc) or Hydrator (https://github.com/DocNow/hydrator).
