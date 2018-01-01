# python_nltk

## High level steps

  - tokenlizing:
  - remove stop word:
```
Text may contain stop words like ‘the’, ‘is’, ‘are’. Stop words can be filtered from the text to be processed.
```
 - stemming:
```
A word stem is part of a word. It is sort of a normalization idea, but linguistic.
For example, the stem of the word waiting is wait.
```
![alt text](https://pythonspot-9329.kxcdn.com/wp-content/uploads/2016/08/word-stem.png)

 - speech tagging:
 ```
Given a sentence or paragraph, it can label words such as verbs, nouns and so on.

POS tag list:

    CC coordinating conjunction
    CD cardinal digit
    DT determiner
    EX existential there (like: "there is" ... think of it like "there exists")
    FW foreign word
    IN preposition/subordinating conjunction
    JJ adjective 'big'
    JJR adjective, comparative 'bigger'
    JJS adjective, superlative 'biggest'
    LS list marker 1)
    MD modal could, will
    NN noun, singular 'desk'
    NNS noun plural 'desks'
    NNP proper noun, singular 'Harrison'
    NNPS proper noun, plural 'Americans'
    PDT predeterminer 'all the kids'
    POS possessive ending parent's
    PRP personal pronoun I, he, she
    PRP$ possessive pronoun my, his, hers
    RB adverb very, silently,
    RBR adverb, comparative better
    RBS adverb, superlative best
    RP particle give up
    TO to go 'to' the store.
    UH interjection errrrrrrrm
    VB verb, base form take
    VBD verb, past tense took
    VBG verb, gerund/present participle taking
    VBN verb, past participle taken
    VBP verb, sing. present, non-3d take
    VBZ verb, 3rd person sing. present takes
    WDT wh-determiner which
    WP wh-pronoun who, what
    WP$ possessive wh-pronoun whose
    WRB wh-abverb where, when

```
