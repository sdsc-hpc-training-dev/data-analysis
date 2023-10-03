# Transcript Word Counts
Goal is to retrieve all transcripts and find the words with the highest counts. This is after removing unnecessary words.

## Details
Stopwords were removed using databanks from [NLTK](https://www.nltk.org/search.html?q=stopwords), [SciKit Learn](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.feature_extraction.text), and [locally defined ones](/ignore.txt) (`ignore.txt`). Results are in the `transcript_word_counts.csv`.

## Shortcomings
I was only able to pull 23 transcripts using the defined parameters. There could be more overhead work into this.