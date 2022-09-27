# Shopify-product-categorization
I used two different approaches for feature extraction, word embedding, and tf-idf
vectors. A total of 4 different methods have been used to solve this problem.
For the first feature extraction approach, to confect input string, I have used two
methods.<br>
1. **[Method #1]**<br>
Making strings by concatenating title and tags columns of the data frame without
any previous preprocessing. Filtering bad characters and tokenization were
applied later on to these strings using keras.preprocessing methods.
2. **[Method #2]**<br>
In this method, at first, I applied preprocess methods on tags and titles
separately, and then by concatenating these two provided lists, the input strings
were created.
3. **[Method #3]**<br>
Extracting tf-idf vectors on rejoining manually-preprocessed tokens
4) **[Method #4]**<br>
I concatenated title and tags for each row and used an extra punctuation removal
step then extracted the tf-idf vector for each input string.
