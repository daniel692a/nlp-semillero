# Tokenization and Text Normalization

> Corpus:  Collection of text and documents, for example: a **dataset** of news

Corpus -> Documents -> Paragraphs -> Sentences -> Tokens

> Tokens: Smaller units of text (words, phrases, ngrams)

## Ngram: Combinations of N words / character together
Example of Ngram:
> Sentence: I love my phone

Unigrams(n=1): I, love, my, phone

Bigrams(n=2): I love, love my, my phone

Trigrams(n=3): I love my, love my phone

# Tokenization
**Process** of **splitting** a text object into *smaller units* (***tokens***).
Smaller units : words, numbers, symbols, ngrams, characters.

Common tokenization is Unigram or white space

# Normalization
**Process** of converting a *token* into its *base form*(***morpheme***).
* Helpful is reducing data dimensionality, ***text cleaning***
**Morpheme**: Base from of a word

## Structure of token:
> <prefix><morpheme><suffix>
Example:
> Antinationalist: ANTI + national + IST

### Types:
* Stemming: elementary rule based process or removal of inflectional forms from a token
> Outputs the stem of a word
  
| Form | Suffix | Stem |
| ---- | ------ | ---- |
| studies| -es | studi |
> May generate non-meaningful terms 
* Lemmatization: systematic process for reducing a token to its lemma
> Make use of vocabulary, word structure, part of speech tags and grammar relations

Example of lemmatization:

```
am, are, is
>>be

  
running, ran, run, rans
>>run
```


