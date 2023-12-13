# CapeStart-ML-Assessment

I initiated the task by performing data cleaning and preprocessing. This involved dropping irrelevant columns, addressing missing values in the 'Tonality' column using the mode, and applying label encoding to both the target variable 'Article Type' and the 'Tonality' column. Further, I executed vectorization for text columns using the 'bert-base-nli-mean-tokens' model from SentenceTransformers. Then, I split 80% of the data for training and 20% for testing and applied MinMaxScaler to scale the input features.

For model building, I employed four classification algorithms: Logistic Regression, Support Vector Machine (SVM), Random Forest, and Multinomial Naive Bayes. I conducted Hyperparameter Tuning using GridSearchCV and implemented cross-validation. The SVM model emerged as the best, based on the chosen parameters.

I displayed accuracy scores, confusion matrices, and classification reports showcasing precision, recall, accuracy, and F1 metrics for the best model. Additionally, I attempted to extract Headings and Full_Article from the provided article URLs in the unknown_article.csv file and predict the article types for the extracted data. Unfortunately, I was unable to complete these final two steps due to time limitations and the processing speed of my system.
