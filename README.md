# TP_NLP

### TP1: Preprocessing Text Data for Twitter Customer Support Dataset

In this TP (Training Project), we worked with the Twitter Customer Support dataset. Our goal was to apply various preprocessing approaches to a text column containing tweets from Twitter users using the Natural Language Toolkit (NLTK) library. The following steps were taken in our preprocessing pipeline:

1. **Converting Text to Lowercase:** We began by converting the entire text to lowercase. This step ensures that the text is uniform and not case-sensitive, which can be useful for various NLP tasks.

2. **Removing Punctuation and Emojis:** To clean the text further, we removed punctuation and emojis from the messages. This step helps eliminate non-textual characters and special symbols that might not be relevant for analysis.

3. **Tokenization:** We applied tokenization to the text, breaking it down into individual words or tokens. Tokenization is a fundamental step in NLP and is necessary for further analysis.

4. **Eliminating Stop Words:** Stop words are common words (e.g., "the," "and," "in") that often do not carry significant meaning in NLP tasks. We removed these stop words from the text to focus on content words.

5. **Lemmatization:** Finally, we applied lemmatization to the text. Lemmatization reduces words to their base or root form. This step standardizes the words and helps in grouping variations of the same word.

As a result of these preprocessing steps, we obtained clean and structured text data that can be used for various NLP tasks, such as sentiment analysis, topic modeling, or classification. For a detailed walkthrough of the preprocessing process, please refer to the accompanying Jupyter notebook. 
