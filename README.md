# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Anorexia Nervosa Predictor Web App

## Introduction

TBA

## Problem Statement

TBA

## Background

**Intermittent Fasting (IF):**
Intermittent Fasting is a popular health trend characterized by controlled fasting and eating patterns. It is often adopted for weight management and overall wellness. Individuals practicing IF alternate between periods of fasting and eating, with various methods and schedules available.

**Anorexia Nervosa (AN):**
Anorexia Nervosa is a severe mental health disorder marked by extreme dietary restriction, an intense fear of gaining weight, and a distorted body image. It is a life-threatening condition that requires specialized treatment and support.

## Datasets

### Data Collection
We obtained data for this project through the use of web scraping and Natural Language Processing (NLP) techniques. We collected Reddit posts related to anorexia nervosa from two subreddits:

1. [r/AnorexiaNervosa](https://www.reddit.com/r/AnorexiaNervosa/)
2. [r/intermittentfasting](https://www.reddit.com/r/intermittentfasting/)

We used the PRAW library and a custom Reddit scraper to collect the data.

## Data Dictionary

Here's a data dictionary for the key columns used in this project:

| Column                             | Datatype  | Explanation                                           |
| ---------------------------------- | --------- | ----------------------------------------------------- |
| **title**                          | object    | Title of the Reddit post                              |
| **post_text**                      | object    | Text content of the Reddit post                       |
| **id**                             | object    | Unique identifier for the post                        |
| **score**                          | int64     | Score or upvotes of the post                          |
| **total_comments**                 | int64     | Total number of comments on the post                  |
| **post_url**                       | object    | URL of the post                                        |
| **subreddit**                      | object    | Subreddit where the post was made                      |
| **post_type**                      | object    | Type or format of the post                             |
| **time_uploaded**                  | object    | Timestamp when the post was uploaded                   |
| **punctuation_removed_title_and_text**  | object    | Title and text content with punctuations removed        |
| **title_text_stemmed**             | object    | Title and text content after stemming                  |
| **title_text_lemmatized**          | object    | Title and text content after lemmatization             |

## Conclusion

TBA

## Recommendations

TBA

---

For any inquiries or assistance related to the Anorexia Nervosa Predictor Web App, please feel free to contact us.
