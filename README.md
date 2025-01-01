# NLP and Text Processing Techniques

This repository contains Python implementations of foundational concepts and techniques in Natural Language Processing (NLP) and Text Processing. These methods are essential for preprocessing and analyzing textual data for various machine learning and data science tasks.

## Table of Contents
1. [Tokenization](#tokenization)
2. [n-grams Extraction](#n-grams-extraction)
3. [Stemming](#stemming)
4. [Lemmatization](#lemmatization)
5. [Stop Words Removal](#stop-words-removal)
6. [Text Normalization](#text-normalization)
7. [Spelling Correction](#spelling-correction)
8. [Parts of Speech (POS) Tagging](#parts-of-speech-pos-tagging)
9. [Bag of Words (BoW)](#bag-of-words-bow)
10. [TF-IDF](#tf-idf)
11. [Text Similarity](#text-similarity)
12. [Language Detection](#language-detection)
13. [Feature Engineering](#feature-engineering)
14. [Additional Concepts](#additional-concepts)

---

## Tokenization
### Code Includes:
- Basic word and sentence tokenization.
- Various tokenizers from NLTK:
  - Tweet Tokenizer
  - Multi-Word Expression (MWE) Tokenizer
  - Regular Expression Tokenizer
  - Whitespace Tokenizer
  - WordPunct Tokenizer

---

## n-grams Extraction
### Techniques Covered:
1. Custom-defined function for n-grams.
2. Using NLTK's `ngrams` method.
3. Leveraging TextBlob for n-grams.

---

## Stemming
### Techniques Covered:
- **Porter Stemmer**: Simplifies words to their root form.
- **Regexp Stemmer**: Applies custom rules for stemming.

---

## Lemmatization
### Techniques Covered:
- **WordNet Lemmatizer**: Converts words to their base form using lexical knowledge.
- Sentence-level lemmatization for enhanced text understanding.

---

## Stop Words Removal
### Features:
- Default stop words from NLTK.
- Custom stop word lists for specific use cases.

---

## Text Normalization
### Includes:
- Replacing abbreviations and codes with full forms.
- Standardizing text for uniformity.

---

## Spelling Correction
### Tools Used:
- **Autocorrect Library**: Fixes common spelling mistakes in text.

---

## Parts of Speech (POS) Tagging
### Details:
- POS tagging using NLTK to label words with grammatical tags like nouns, verbs, etc.

---

## Bag of Words (BoW)
### Techniques Covered:
- Generating BoW representation using Scikit-learn's `CountVectorizer`.
- Limiting the vocabulary to the top N features.

---

## TF-IDF
### Techniques Covered:
- Generating term-frequency inverse document frequency vectors.
- Extracting top N frequent terms for feature selection.

---

## Text Similarity
### Techniques Covered:
- **Jaccard Similarity**: Measures word overlap.
- **Cosine Similarity**: Uses TF-IDF for semantic comparison.

---

## Language Detection
### Tools Used:
- **LangDetect**: Identifies the language of a given text.
- **SpaCy with LangDetect**: Advanced language identification.

---

## Feature Engineering
### Includes:
- Extracting text features like:
  - Number of words.
  - Presence of WH-words.
  - Polarity and subjectivity.

---

## Additional Concepts
### Explored Topics:
- Singularization and pluralization of words.
- Language translation using TextBlob.

---
