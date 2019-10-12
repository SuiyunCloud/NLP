# Basic NLP operations
1. Regex
* regex algorithms check string against the language rules
2. Tokenization
* Split test into words and sentences
3. Stop Word Filtering
* Stop word - words unnecessary to the meaning for an NLP task
* predifined in a list
4. Tagging
* Named entity recognition(NER)

    * Named entity - person, location, organization
    * NER - tagging named entities
    * Can be done with lists of entities and special algorithms

* Parts-of-speech tagging

    * Determine grammatical groups of words (e.g. subject, verbs, etc.)
    * Done with lists of words/part-of-speech combinations and special algorithms
5. Stemming
* Simplifying words in order to reduce the vocabulary. Reducing the vocabulary will reduces dimensionality and to make processing more efficient
* Stem: base word without prefixes or suffixes(root word)

    Example:

        transformation -> transform
        conditional -> condition

* Stemming is usually done with a set of rules (e.g. remobve 'ation' from all words with long enough stems)