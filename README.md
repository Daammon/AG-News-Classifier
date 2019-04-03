# AG-News-Classifier
2 Versions for the AG News classifier using Bert and AWD-LSTM
The AG News corpus consists of news articles from the AG’s corpus of news articles on the web pertaining to the 4 largest 
classes.
The dataset contains 120,000 training examples for each class 7,500 examples for each class for testing. 

Two versions of the classifier have been implemented. One using AWD-LSTM in Pytorch/FastAI and one using Bert in Pytorch
based on the repository of hugginface(https://github.com/huggingface/pytorch-pretrained-BERT) 

With AWD-LSTM the accuracy obtained in the test set was 92.2% after 10 epocs of finetuning the language model and 3 epocs of training the classifier 
and with Bert I reached 94.22% after 3 epocs of finetuning the language model and 2 epocs of training the classifier.
