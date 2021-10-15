# Parts of Speech tags
> Defines the syntactic context and role of words in the sentence
## Common POS Tags:
* Nouns
* Verbs
* Adjectives
* Adverbs

Sentence: David has purchased a new laptop from Apple Store

**NNP(Proper noun, singular)**: David

**VBZ(Verb, 3rd person singular present)**: has

**VBN(Verb, past participle)**: purchased

**DT(Determiner)**: a

**JJ(Adjective)**: new

**NN(Noun, singular or mass)**: laptop

**IN(Preposition or subordinating conjunction)**: from

**NNP(Proper noun, singular)**: Apple

**NN(Noun, singular or mass)**: Store

Defined by their relationship with the adjacent words

## Penn Treebank Parts of Speech Tags
![Table](../imgs/part-speech-tag.png)

### Uses
* Text cleaning
* Feature engineering tasks
* Word sense disambiguation

# Constituency Grammar
> **Constituents**: Words/ phrases / group of words

> Constituency Grammar: Organize any sentence into constituents using properties.

> Properties: Part of Speech Tags / Noun phrases / Verb Phrases

***Example***:

Sentence: <subject><context><object>

<subject>: The cats / The dogs / They

<context>: are running / are barking / are eating

<object>: in the park / happily / since the morning

# Dependency Grammar
> Words of a sentence depends on which other words (dependencies)

> Organize the words of a sentence according to their dependencies

## Use cases

* Named entity recognition
* Question answering systems
* Coreference resolution
* Text Summarization
* Text Classifications