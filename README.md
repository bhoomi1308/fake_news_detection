# fake_news_detection

Social media interaction especially the news spreading around the network is a great source of information nowadays. Inspite of this great usage some sources are spreading fake news, gossips about organization, individuals.

This demonstrates the detection of fake news in the network using python libraries, data analysis concepts. The data set has some sentences or documents about political issues.

The data we use is usually split into training data and test data. The training set contains a known output and the model learns on this data in order to be generalized to other data.
tfidf_vectorizer=TfidfVectorizer(stop_words='english')
which is to convert a collection of raw documents to a matrix of TF-IDF features. TF-IDF is frequency–inverse document frequency, is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus.

Stopwords are the words in english which donot give much value to the sentences. During preprocessing of data, stopwords are removed.

Passive Aggressive Algorithms are a family of online learning algorithms. Predict method is to predict the label of a new set of data. If the model predicts the value correctly, then the model is kept as it is.If the model is predicts incorrectly, some changes are made to make the predictions correct.

The model classifies the given sentence into fake or real and gives 92.8% accuracy.
