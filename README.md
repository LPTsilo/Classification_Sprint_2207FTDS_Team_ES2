# Classification_Sprint_2207FTDS_Team_ES2 #
## EDSA - Twitter Sentiment Classification ##
We joined the EDSA Twitter Sentiment Classification competition on Kaggle, with `me` as the team leader. Our goal was to analyze the sentiment of tweets using classification models and achieve a high F1 score.

After trying different models, we found that the `Support Vector Machine (SVM)` model worked best for our needs. We trained the SVM model on a dataset of labeled tweets, and achieved an F1 score of `0.63916`, which placed us at 56th on the competition leaderboard.

To showcase our model, we created a Streamlit app that allows users to enter a tweet and see its sentiment classification. The app is easy to use and provides an interactive way to demonstrate the capabilities of our model. 

For the demonstration of the app go [here]("https://github.com/LPTsilo/classification-predict-streamlit-template")

Overall, we are proud of our work and excited to continue learning and improving our skills in data science and machine learning.

## About ##
Many companies are built around lessening one’s environmental impact or carbon footprint. They offer products and services that are environmentally friendly and sustainable, in line with their values and ideals. They would like to determine how people perceive climate change and whether or not they believe it is a real threat. This would add to their market research efforts in gauging how their product/service may be received.

With this context, EDSA is challenging you during the Classification Sprint with the task of creating a Machine Learning model that is able to classify whether or not a person believes in climate change, based on their novel tweet data.

Providing an accurate and robust solution to this task gives companies access to a broad base of consumer sentiment, spanning multiple demographic and geographic categories - thus increasing their insights and informing future marketing strategies.
## Evaluation
### The evaluation metric ###
Mean F1-Score. The F1 score, commonly used in information retrieval, measures performance using using the statistics precision and recall.

Precision is the ratio of true positives to all predicted positives. Recall is the ratio of true positives to all actual positives.
The F1 metric weights recall and precision equally, and a good retrieval algorithm will maximize both precision and recall simultaneously. Thus, moderately good performance on both will be favored over extremely good performance on one and poor performance on the other.
## Data ##
#### Where is this data from?
The collection of this data was funded by a Canada Foundation for Innovation JELF Grant to Chris Bauch, University of Waterloo. The dataset aggregates tweets pertaining to climate change collected between Apr 27, 2015 and Feb 21, 2018. In total, 43,943 tweets were collected. Each tweet is labelled as one of 4 classes, which are described below.

#### Class Description

- 2 News: the tweet links to factual news about climate change

 - 1 Pro: the tweet supports the belief of man-made climate change

- 0 Neutral: the tweet neither supports nor refutes the belief of man-made climate change

- -1 Anti: the tweet does not believe in man-made climate change Variable definitions

#### Features

sentiment: Which class a tweet belongs in (refer to Class Description above)

- message: Tweet body

- tweetid: Twitter unique id








