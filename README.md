# Fake News Detection

## Overview  
The topic of fake news detection on social media has recently attracted tremendous attention. The basic countermeasure of comparing websites against a list of labeled fake news sources is inflexible, and so a machine learning approach is desirable.  Our project aims to use Natural Language Processing to detect fake news directly, based on the text content of news articles. 
<br>
It is built using python and Flask . Flask is a small and lightweight Python web framework that provides useful tools and features that make creating web applications in Python easier. It gives developers flexibility and is a more accessible framework for new developers since you can build a web application quickly using only a single Python file.
## Problem Definition
Develop a machine learning program to identify when a news source may be producing fake news. We aim to use a corpus of labeled real and fake new articles to build a classifier that can make decisions about information based on the content from the corpus. The model will focus on identifying fake news sources, based on multiple articles originating from a source.  Once a source is labeled as a producer of fake news, we can predict with high confidence that any future articles from that source will also be fake news.  Focusing on sources widens our article misclassification tolerance, because we will have multiple data points coming from each source.  

The intended application of the project is for use in applying visibility weights in social media.  Using weights produced by this model, social networks can make stories which are highly likely to be fake news less visible.
## Live link
https://say-no-to-fake-news.herokuapp.com/prediction
<br>
## Dataset Description

* train.csv: A full training dataset with the following attributes:
  * id: unique id for a news article
  * title: the title of a news article
  * author: author of the news article
  * text: the text of the article; could be incomplete
  * label: a label that marks the article as potentially unreliable
    * 1: fake    * 0: real

* test.csv: A testing training dataset with all the same attributes at train.csv without the label.
# Work Flow
![tsa2](https://user-images.githubusercontent.com/68144680/170679357-7d826ea9-9659-4063-9bb3-283e4c343a70.png)


## ScreenShots



![fnd1](https://user-images.githubusercontent.com/68144680/170677878-71a68055-3b6f-464a-8fd3-f6ce5a276909.png)
![fnd2](https://user-images.githubusercontent.com/68144680/170677883-71dc7790-f8e5-4e14-8e11-5567ac97b483.png)
![fnd3](https://user-images.githubusercontent.com/68144680/170677885-2773c818-0ce9-45d3-9c41-7d59e123a234.png)
![fnd4](https://user-images.githubusercontent.com/68144680/170677889-acd29fee-f194-4a52-839e-c4919535a96f.png)

![fnd5](https://user-images.githubusercontent.com/68144680/170677890-3f4c2fee-e675-4bf0-882f-6dd626f61e4e.png)


![fnd6](https://user-images.githubusercontent.com/68144680/170677871-8329f1c8-1084-4b95-b702-6a33519c5aba.png)


