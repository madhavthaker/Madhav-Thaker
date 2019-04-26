# Data science portfolio by Madhav Thaker

This portfolio is a compilation of notebooks which I have built for various personal projects and experiments. I've split up all of the projects based on solution categories.

Professional projects and accomplishments can be found on my [LinkedIn](https://www.linkedin.com/in/madhavthaker/).

## Natural Langauge Processing 

### Supervised Learning

**Automatic Essay Grading Tool**

Developed an Automatic Essay Grading tool in Python that utilizes TensorFlow to build a Four-Layer feed-forward neural network. Additionally, by utilizing the Natural Language Tool Kit (NLTK) package, I built a regression model that incorporates features such as grammar and sentiment to grade test essay sets. A Spearman's Correlation of approximately 0.90 was achieved. The code can be found [here.](https://github.com/madhavthaker/AES)

**IMDB Sentiment Analysis**

Leveraged the IDMB Sentiment dataset of 50,000 movie reviews and their corresponding sentiments (1,0) to build a sentiment analysis model. Throughout the process, I compared three vectorization techniques:

1. TF-IDF
2. Word2Vec
3. Universal Sentence Embeddings

The main motive was to compare vectorization techniques so I just used Logistic Regression for my model. Unsurprisingly, we found that the Universal Sentence Embeddings performed the best with an F1 score of #.##. The code can be found [here]().

### Unsupervised Learning 

**Comparing Various Extractive Text Summarization Techniques**

Developed a notebook comparing the approach and results of three extractive text summarization techniques:

1. Sentence scoring based on word frequency
2. TextRank using Universal Sentence Encoder
3. Unsupervised Learning using Skip-Thought Vectors

Results showed that approach three did the best job of extracting the key themes within the passage. I've published these findings in a "Towards Data Science" [Medium article](https://towardsdatascience.com/comparing-text-summarization-techniques-d1e2e465584e). The notebook can be found [here.](https://github.com/madhavthaker/text_summarization/blob/master/Text_Summarization.ipynb) 

**Presidential Inauguration Sentiment Comparison**

Utilized NTLK and TextBlob packages to analyze the sentence by sentence sentiment of Obama and Trump's Inauguration Speeches. Using GGPlot, this sentiment was visualized to help analyze the Presidents’ emotion as each speech progressed. This analysis was done in Python. The code can be found [here](https://github.com/madhavthaker/InuagurationComparison/blob/master/Inauguration%20Analysis.ipynb). Here is the final output visualization:

![Image](https://imgur.com/3TGUuzv)

## Computer Vision

**Emotion Detection**

Developed a Convolutional Neural Network to analyze the emotion (7 emotional states) in a specific greyscale static image. Utilized Tensorflow to construct the Neural Network and visualized its performance and architecture using Tensorboard. The code can be found [here](https://github.com/madhavthaker/EmotionDetection/blob/master/projectscript.py)

## Structured Data

### Supervised Learning

**How well would Messi do in a different league?**

Developed a negative binomial model to predict the number of goal Lionel Messi would score in a different league. Only leveraged defense as a predictor and plan to incorporate weather and historical record against a specific team. Coded in R and can be found [here](https://github.com/madhavthaker/MessiPredictions/blob/master/Goals%20in%20Other%20Leageus.R). Blog post can be found [here.](http://madhavthaker.com/2016/08/25/would-messi-make-it-outside-of-spain/) 

### Unsupervised Learning & EDA

**Exploring NYC Taxi Trip Data**

Developed a EDA kernel for the "New York City Taxi Trip Duration" kaggle competition. Data consisted of start and end coordinates for taxi trips along with their corresponding times. Kernel can be found [here](https://www.kaggle.com/madhavt/yet-another-data-visualization-notebook)
