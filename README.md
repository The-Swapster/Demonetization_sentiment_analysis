# Demonetization_sentiment_analysis
**Aim:** Perform sentiment and emotion analysis on tweets made by indians during demonetization
**Steps**
* Reading Data
* Droping columns which are not required
* Checking for null values
* Converting to lower case
* Removing punctuations
* Lemetizing and tokenizing tweets
* Removing stopwords and storing in a seperate column
* Removing 'rt' from the tokenized text
* Counting word frequency
* Making word cloud of top 100 words
* Finding emotions using text2emotion
* Seperating emotions in columns
* Making the value of emotion 1 where ever it is present for simplicity
* Applying decison tree and random forest for multi label classification
* Using SentimentIntensityAnalyzer for finding emotions
* Seperating sentiments in columns
* Making the value of sentiment 1 where ever it is present for simplicity
* Applying decison tree and random forest for multi label classification
* Forming pie chart and bar graph for sentiments to find the sentiment of people on the decision
* Forming pie chart for emotions to find the emotions of the people on the decision

**Conclusion**
* The word cloud shows that demonetization is the most occuring word, followed by india, modi, pm, and narendra
* The results for random forest has outperformed decision tree, giving an accuracy of 80.32% in case of emotion analysis
* The results for random forest has outperformed decision tree, giving an accuracy of 83.70% in case of sentiment analysis. 
* Sentiment classification gives better results than emotion classification
*
* In emotion analysis we can see that the most prominet emtion is fear, as citizen were anticipating a lot of circumstances which could follow demonetization, the next most prominet emotion was surprise, indicating that people were taken by surprise by the steps taken by the Govenment of India. As seen, sad is also prominent in the pie chart
