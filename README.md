# n-gram-models
Built a simple language model that predicts the next word in a sentence based on n-gram statistics

# Problem Statement
1. Data collection and preprocessing:
  - Collect a dataset of text. You can use the text corpora available in the nltk library,
such as reuters or gutenberg.
  - Clean and preprocess the data (e.g., remove special characters, convert to lower-case)
  - Tokenize the text into words.
2. Model implementation:
(a) Create n-grams from the tokenized text.
(b) Calculate the frequency of each n-gram in the dataset.
(c) Write a function to calculate the probability of a word following a given (n − 1)-
gram.
(d) Write a function to predict the next word given a sequence of words based on these
probabilities.
(e) Write a function to generate a sentence of a specified length given a prefix of (n−1)
words.
(f) Implement smoothing techniques (like Laplace smoothing) to handle the issues of
zero probabilities for unseen n-grams.
3. Testing and evaluation:
(a) Test the model with different (n − 1)-gram inputs to see how it predicts the next
word.
(b) Compare the performance of different n values (e.g., bigrams vs. trigrams).
4. Write a short report discussing your results.
5. Bonus: Create a simple user interface where users can enter some prefix and get a
completion of words up to a specified length.
