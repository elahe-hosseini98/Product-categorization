# Product-categorization
I used two different approaches for feature extraction, word embedding, and tf-idf
vectors. A total of 3 different machine learning and deep learning models have been used to solve this problem.<br>
1. **[Method #1]**<br>
In this method, at first, I applied preprocess methods on tags and titles
separately, and then by concatenating these two provided lists, the input strings
were created and a **Transformer** based DL model were applied on the data.
2. **[Method #2]**<br>
With the same steps as solution#1 I preprocessed the dataset and then I applied and **LSTM** network on them.
3. **[Method #3]**<br>
Extracting **tf-idf** vectors on rejoining manually-preprocessed tokens then tested multi ML models
on tf-idf feature vectors.
