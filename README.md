# BERT-sentiment-analysis
BERT stands for Bidirectional Encoder Representations from Transformers.
BERT’s key technical innovation is applying the bidirectional training of Transformer, a popular attention model, to language modelling. This is in contrast to previous efforts which looked at a text sequence either from left to right or combined left-to-right and right-to-left training. The paper’s results show that a language model which is bidirectionally trained can have a deeper sense of language context and flow than single-direction language models.\
This project uses a dataset of tweets containing 3085 tweets divided into multiple classes. Although the dataset contains many different classes, only 6 classes have been used for final classification. Other classes were removed in the data preprocessing stage as they were mixed sentiments classes e.g. sad|disgust. 
The project has been done by finetuning BERT using Pytorch and scikit-learn. The optimizer used is Adam with weight decay.\
Here we have a significant class imbalance problem so the final model is judged based on the f1 score obtained.
The final model achieved an f1 score of 0.8758.
