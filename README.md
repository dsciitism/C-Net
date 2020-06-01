# C-Net
C-Net: Contextual Network for Sarcasm Detection

# Why it is Important ?
1. Classifying an utterance as sarcastic or not in isolation can be futile since most of the time the sarcastic nature of a sentence heavily relies on its context. 
2. It plays a crucial role in improving the effectiveness of chatbot systems. Sentiment classification systems can fail in the absence of a robust sarcasm detection system. A sarcastic sentence can express a negative sentiment even with the presence of positive or neutral sentiment words in that sentence. 
3.  It can make an artificially intelligent agent closer to imitate human behaviour and enable it to better understand true intentions and emotions of humans.

# Main Challenge
To use the dialogue context information of an utterance effectively to decide its sarcastic nature.

# Methods Used:
1. Baseline methods: Logistic Regression, Naive Bayes, SGD Classifier, XGBoost, SVM, Vanilla RNN, Bi-LSTM.
2. Pre-trained Networks: DeepMoji, ELMo, XLNet, BERT, RoBERTa.
3. C-Net (Our approach).
4. Timestamping.

Baseline methods and Pre-trained networks classified responses in isolation, without any context information.
C-Net effectively utilises partial context information.
Timestamping utilises complete context information.
