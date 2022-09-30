# Text_Feature_Extraction
A] Text_Feature_Extraction_ML:
- Uses SMSSpamCollection dataset that contains more than 5 thousand SMS phone message
- classify sms message into label of ham or spam using message length and punctation count.
- Use Logistic Regression classifier, Naive Bayes Classifier and Support Vector classification (SVC) ie C-Support Vector Classification for training the dataset and predicating whether the sms msg is ham or spam for new dataset. 
- SVC model predicated better accuracy in comparison to other two approaches.

B] Text_Feature_Extraction_Vectorization:
- classify sms message into label of ham or spam using the content of the message.
- TfidfVectorizer convert a collection of raw documents to a matrix of TF-IDF features.
- TfidfVectorizer is equivalent to CountVectorizer followed by TfidfTransformer.
- CountVectorizer performs text preprocessing, tokenizing, filter out stopwords. CountVectorizer builds a dictionary of features and transforms documentes to feature vectors.
- Perform training of the dataset using LinearSVC.  LinearSVC handles sparse input better, and scales well to large numbers of samples.
- Build a pipeline that performs vectorization and classification in a single step. Use the pipeline to fit the train dataset and predict the result for new test dataset

- Both LinearSVC and C-Support Vector Classification comes from sklearn.svm 
