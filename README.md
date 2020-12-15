In this project, we designed a scoring system that captures the overarching concept of different levels of “inflammatory” comments on Reddit, performed annotations based on detailed guidelines, and extracted leading key words that are likely causing higher levels of “inflammatory” comments. We trained an bi-direcitonal LSTM model with an attention layer on a regression task in Pytorch to extract contributing keywords of higher inflammatory comments. Please see the heatmap example of inflammatory comment with highlighted intriguing keywords. 

In order to utilize attention layer notebook, you need to obtain wording embedding files from Stanford NLP group at:
https://nlp.stanford.edu/projects/glove/

