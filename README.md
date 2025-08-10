Word2Vec is a word embedding technique developed by Google in 2013 that represents words as dense numerical vectors in such a way that words with similar meanings are located close to each other in the vector space.

Instead of treating words as discrete tokens (like in one-hot encoding), Word2Vec learns semantic relationships between words from large text corpora.

🔹 How It Works
Word2Vec is built on the idea that "words used in similar contexts tend to have similar meanings" (distributional semantics).
It uses a shallow neural network to learn these relationships through one of two architectures:

CBOW (Continuous Bag of Words)

Predicts the target word based on its surrounding context words.

Example: "The cat ___ on the mat" → predicts sat.

Skip-gram

Given a target word, predicts the surrounding context words.

Example: Input sat → predicts The, cat, on, the, mat.

🔹 Why It's Useful
Captures semantic similarity:

king - man + woman ≈ queen

More memory-efficient than one-hot encoding (dense vectors vs. sparse).

Useful in NLP tasks like:

Text classification

Sentiment analysis

Machine translation

Question answering

