---
title: Improving Accessibility for Shanghainese Speakers with Screen Reader for Mandarin
description: "The goal of our project was to create a screen reader extension to translate characters in Mandarin Chinese into Shanghainese audio. This will help visually-impaired Shanghainese navigate the web in China."
date: 2020-04-27 # Please use YYYY-MM-DD format. 
authors: 
 - Akhila Chinepall
 - Havi Nguyen
 - Joan Martinez
# github: https://github.com/JonathanReeve/example-github-repo # Optional
---

### Abstract 
For our project, we developed a screen reader and a LSTM machine translator. Our objective was to combine an application tool with our language model to perform a translation of Mandarin text into Shanghainese audio to help visually impaired Shanghainese speakers interact with the Internet. We hope to build off of our current work and eventually expand to provide screen readers for other Chinese dialects. This will preserve other dialects and make the Internet more equitable for visually impaired Chinese dialect speakers. We were able to create an individual screen reader using JavaScript that highlights a selected portion of text, parse through, and output the highlighted text into English. Our LSTM-model was able to accurately translate portions of Mandarin text into Shanghainese text. 

### Project Goal 
The goal of our project was to create a screen reader in the form of either a web extension or an application that would be able to translate characters in Mandarin Chinese into Shanghainese audio. We thought of this because screen readers are an essential form of assistive technology that aids the visually impaired, allowing for them to interact with web pages. Screen reader technology at the moment is very limited in its scope. Most screen readers are only compatible with English based web pages in terms of interpretation capabilities. Other screen readers can interpret languages written in Latin script, but very few can handle non-Latin Script. Additionally, accessibility tools geared for Chinese speakers are mainly geared for Mandaring speakers and the other dialects are often ignored. Shanghainese is a common dialect in China that???s often overlooked when creating accessibility tools for the visually impaired. We hope that our Mandarin text to Shanghainese audio screen reader extension will bridge the gap in Chinese dialect accessibility tools.  Eventually, we plan to build upon this project to create screen readers that can translate Mandarin text into other Chinese dialect audio. This tool helps Shanghainese speakers navigate and interact with the Internet in their native language.  

### Relationship to Language Justice  
This project promotes Language Justice for Shanghainese speakers, specifically those living underneath the current Chinese government. The Chinese government has made a big push for Mandarin as the uniform language of China. This comes at the cost of losing the variety of Chinese dialects that exist within the country. Researchers have shown that the Shanghainese dialect has been on a rapid decline and will die in 50 years if preservation actions are not taken. Numerous Shanghainese speakers conformed to using Mandarin as their main language since there are not many existing tools to support their own dialect. Current statistics and mathematical models have proven the process of how dominating one language can lead to weaker, minority languages to become extinct overtime. However, according to findings from arXiv, the effects shown in these models can be mitigated through the introduction of bilingual speakers. Bilingual speakers are important as a linguistic force in their own communities and lead for a co-evolution of two languages. These trends can be observed with Mandarin and Shanghainese speakers. Mandarin is the dominant language and Shanghainese is a dialect that is used by a subset of communities in China. Through building accessible tools that will support Shanghainese speakers, this will reduce the dominant
effects that Mandarin has on the community. This is due to the different language pronunciations of the same text. By Allowing these two languages to flourish, the communication and cultural exchange between these communities and a language dialect will increase to  avoid extinction.

### Data  
The data used in our model was a dataset that contained the mappings of words/phrases in both Shanghainese and Mandarin. The dataset laid out the text-to-test translations pairings in both dialects and mapped to an audio file of the Shanghainese pronunciation of the text. 
 
In addition to the dataset and audio files, we obtained a repository called Shanghainese-Audio-Crawler9 that enables our team to conduct audio segmentation amongst audio in both Shanghainese and Mandarin. This audio crawler could obtain Mandarin text and distinguish the Mandarin text from Shanghainese to properly label the parsed translation as audio outputs. These audio output files could then be utilized in our model. 

### Methodology
In the process of designing our language translation model we utilized NTUT+III???s model for a Chinese text-to-speech system. We then followed that by training our unique data set that contained Mandarin and Shanghainese words and phrases and tokenized the inputted text. With these tokenized values we were able to establish training and test sets that would then be used for prediction and validation.  

### Conclusion
In conclusion, we were able to lay the foundation of building a screen reader for visually-impaired Shanghainese speakers to interact with online Mandarin content. This project is significant in helping preserve language diversity in China. The Shanghainese dialect has been on the rapid decline as Mandarin became more mainstream. Through having tools purposely built for Shanghainese speakers, these speakers will still be able to interact and operate the web in their own dialect rather than conforming to Mandarin. We were able to train a LSTM machine translator with an existing dataset we found and resulted in the model???s value loss improving with each epoch layer. Furthermore, we were able to build a screen reader that could parse through text and produce an audio output to the user. These steps in our project brought us closer to our goal of preserving language diversity for Shanghainese speakers. 

