# Depression-Intensity-Estimation-via-Social-Media-A-Deep-Learning-Approach

Depression has emerged as a significant societal problem in recent times, leading to a major cause of suicide, especially among teenagers. The ongoing COVID-19 outbreak has compelled affected countries to implement social distancing and lockdown measures, resulting in increased interpersonal isolation and raising serious concerns about mental health and depression. Traditionally, diagnosing individuals with depression relied on face-to-face interviews by clinical psychologists, following specific clinical depression criteria. However, many patients tend to avoid consulting doctors in the early stages of depression. In today's digital age, people increasingly turn to social media to express their emotions and moods. This article aims to address the issue by predicting depressed users and estimating the intensity of their depression using data from social media, specifically Twitter. The objective is to create an early warning system to identify individuals who might be in need of assistance. The approach involves modeling the problem as a self-supervised learning task. To annotate the Twitter data, an expert psychologist followed the Diagnostic and Statistical Manual of Mental Disorders (DSM-5-TR) in a self-supervised manner. A diverse set of features, including emotional, topical, and behavioral aspects, are extracted to represent each user. These features are then used to train a small long short-term memory (LSTM) network with Relu as an activation function to predict depression intensities.The article presents the findings of depression intensity analysis from social media, using the BDI-II scale as a reference. This research sheds light on the potential of leveraging social media data to aid in identifying and supporting individuals experiencing depression.

![Scale](/figs/depression_intensity.png) 


## Dataset
Please download the data using the link: [Dep-Depresion](https://github.com/sunlightsgy/MDDL) 

## Pipeline 
![pipeline](figure/Depression.drawio (2).png) 

## Contact
- <a href="https://scholar.google.com/citations?user=3OJbzKYAAAAJ&hl=en">Tabia Tanzin Prama</a>, <a href="#">Md. Saiful Islam</a> and <a href="#">Md Musfique Anwar</a>.

## Acknowledgements
This repository makes liberal use of data repositarites from 
[MDDL](https://github.com/sunlightsgy/MDDL), [NLTK](https://www.nltk.org/index.html), [text-vad](https://github.com/bagustris/text-vad), [Sentiment-Analysis-ANEW](https://github.com/nisarg64/Sentiment-Analysis-ANEW), [SentimentAnalysis](https://github.com/dwzhou/SentimentAnalysis), [topic-modeling-to-identify-depression-markers](https://github.com/abhilashhn1993/topic-modeling-to-identify-depression-markers).
