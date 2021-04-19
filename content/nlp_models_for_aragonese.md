---
title: "NLP Models for Aragonese: Next Word Predictor and Spell Checker"
description: "This project attempted to create educational technological tools, specifically a next word predictor and a spell checker, using Google's BERT tool."
date: 2021-04-16 
authors: 
 - David Giliver
 - Mihika Nadig
 - Soo Rin Lee
github: https://github.com/soorinslee/NLP-Models-for-Aragonese 
---

Aragonese is a low resource Romance language and has minimal technological resources. In order to promote the vitality of Aragonese, this project attempted to create educational technological tools, specifically a next word predictor and a spell checker, using Google's BERT tool. BERT utilizes Aragonese Wikipedia articles to train, and the model was further trained using Aragonese Tweets found on Indigenous Tweets. The next word predictor yielded an accuracy score of 26.79\% for random masked token prediction and 4.61\% for last token prediction. The spell checker yielded an accuracy score of 47.59\%, using a vocabulary of over one hundred languages. The next word prediction error stemmed from a combination of (1) a lack of annotated training data and (2) the nature of Twitter data (i.e., code-switching and real words). Future iterations of the next word predictor will include a revised model: one that better incorporates left and right-hand context for mid-word prediction but also only left-hand context for next word prediction. The spell checker's main source of error stemmed from the fact that non-Aragonese words were included in the spell suggestions; future iterations of the spell checker tool would benefit from an Aragonese-only vocabulary.