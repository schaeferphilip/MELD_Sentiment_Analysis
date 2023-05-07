## MELD Sentiment Analysis

Sentiment analysis project on the MELD dataset from the TV series Friends. Using a deep learning model and natural language processing techniques, this project aims at modeling, predicting and analyzing a database of conversations between the characters of the show.


# Dataset

- MELD (train, test, validate)
- Dataset for emotion recognition in multiparty conversations from the series Friends
- Shape : (9989, 13)
- Columns : 'Utterance', 'Speaker', 'Emotion', 'Sentiment', 'Dialogue_ID',  'Utterance_ID', 'Season', 'Episode', 'StartTime', 'EndTime'


# Data Processing 
- concatenate
- clean text
- categorical value processing

# Model Architecture

![](/readme_images/modelarch.png)

# Model Fitting

![](/readme_images/modelfit.png)


# Data Visualisation

![](/readme_images/graph1.png)

![](/readme_images/graph2.png)


# Model Evaluation

Test Accuracy : 0.9563218355178833 

![](/readme_images/testac.png)

Test Loss :  0.13441912829875946

![](/readme_images/testlo.png)

# Conclusion

In conclusion, the MELD project is an exciting development in the field of natural language processing and emotion recognition. Using a deep learning model, we were able to accurately predict the emotion of a given utterance based on factors such as sentiment and speaker.

Our results showed that the model achieved 96% accuracy, indicating that it can be a useful tool for researchers and developers working on emotion recognition applications.

In the future, the MELD dataset and model can be used for various applications, such as improving mental health interventions and developing chatbots that can detect and respond to users' emotions. In addition, further research can be conducted to explore the model's potential to predict emotions in different languages and cultures.

Overall, the MELD project is an important contribution to the field of emotion recognition and can have a positive impact on society.