# Emotion_dection_in_text

##This study successfully demonstrated the effectiveness of Convolutional Neural Networks (CNN) for emotion detection 
in text, with a focus on comparing various word embedding techniques such as FastText, RoBERTa, and GloVe. The 
research utilized three distinct types of datasets: movie reviews, e-commerce customer feedback, and a combined dataset 
of both. The experiments were conducted across three scenarios: FastText+CNN, RoBERTa+CNN, and GloVe+CNN.

##The results indicate that RoBERTa+CNN consistently outperforms the other methods, achieving the highest accuracy 
across all datasets. In particular, RoBERTa+CNN produced accuracy values of 89.45%, 90.12%, and 89.87% for the 
movie reviews, e-commerce feedback, and combined datasets, respectively. FastText+CNN showed strong performance 
but lagged behind RoBERTa+CNN in terms of precision, recall, and F1-Measure. GloVe+CNN exhibited the lowest 
performance in comparison, highlighting the advantages of more context-sensitive embeddings like RoBERTa. 
The comparison of Precision, Recall, and F1-Measure further supports the superiority of RoBERTa+CNN, reinforcing 
that context-aware embeddings provide better results for emotion detection tasks. This study’s findings emphasize the 
importance of dynamic word embeddings in capturing the nuances of human emotions in text, particularly for tasks like 
emotion classification.

##Suggestions for future research include exploring the integration of CNN with other deep learning architectures, such 
as BiLSTM or LSTM, to enhance emotion detection capabilities. Additionally, further investigations into the use of 
RoBERTa embeddings combined with these models could provide insights into improving classification accuracy. Future 
work could also focus on using more balanced datasets to address any potential biases in emotion class distribution, 
which would likely contribute to more reliable and generalizable emotion detection models. 
This research highlights the potential for improved emotion detection through the use of advanced word embeddings and 
CNN, paving the way for more accurate and contextually aware emotion classification systems in text. 
