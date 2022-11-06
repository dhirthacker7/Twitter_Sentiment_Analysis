# Twitter sentiment analysis (opinion mining)
 
#### Sentiment Analysis is the process of 'Computationally' determining whether a piece of writing is positive, negative, or neutral.
#### It's also known as opinion mining, deriving the opinion or attitude of a speaker.

##### Step 1: Tokenization (dividing para into different sentences and sentences into words)
##### Step 2: Cleaning Data (Removes all these unique characters and words which do not add any value to the analytics part)
##### Step 3: Removing Stopwords (like The, was, he/she) that do not add value to the analytics part.
##### Step 4: Classification: To classify them as to whether it is a positive/negative/neutral word.
###### Positive word: We give a score of +1
###### Negative word: We give a score of -1
###### Neutral: 0
##### Step 5: Apply Supervised Algorithm of classification (machine learning)
###### You train you model with Bag of words or lexicons and test it on the analyzing statement.
###### Lexicons – Dictionary of a pre-classified set of words.
###### Once the model is trained, we can perform the test on the analysis statement. An accurate score will be the classification.
###### If your model is too accurate, then YES (it will be an excellent classification)
##### Step 6: Calculation (final sentiment score of the statement based on polarity)
