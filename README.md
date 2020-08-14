# Fake Tweets Detector

This notebook is an attempt for the [Real or Not? NLP with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started/) Kaggle competition.

## Problem details
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster.

Take this example:

```
On plus side LOOK AT THE SKY LAST NIGHT IT WAS ABLAZE"
```
The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

The challenge is to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. We have access to a dataset of 10,000 tweets that were hand classified.

## Data
This dataset was created by the company figure-eight and originally shared on their [‘Data For Everyone’ website here](https://appen.com/resources/datasets/).
