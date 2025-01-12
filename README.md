# Natural Language Processing (NLP)

NLP is a field of artificial intelligence focused on enabling computers to understand, interpret, and respond to human language. 
Key steps in NLP involve processing text into manageable components to analyse or transform it.

### Tokenization
Tokenization is the process of splitting text into smaller units called tokens, which can be words, phrases, or sentences.

_(Example)_
Input: "Natural language processing is fascinating." <br/>
Tokens: ["Natural", "language", "processing", "is", "fascinating"] <br/>

Applications of Tokenization:<br/>
Basis for further processing like parsing or analysis.<br/>
Prepares text for machine learning models.<br/>

### Stemming
Stemming is the process of reducing words to their base or root form by removing suffixes or prefixes. It often uses heuristic rules.

_(Example)_
Input words: "running", "runner", "runs"<br/>
Stem: "run"<br/>
Common Algorithms for Stemming:<br/>
Porter Stemmer: Uses predefined rules to strip suffixes (e.g., “ing,” “ed”).<br/>
Snowball Stemmer: An advanced version of the Porter Stemmer, with support for multiple languages.

<!--
### Lemmatization (Alternative to Stemming) 
Lemmatization reduces words to their canonical dictionary form (lemma), considering the word’s context and meaning.

_(Example)_
Input words: "running", "better"
Lemmas: "run", "good"
It is more accurate than stemming but computationally more expensive. -->



I used the [NLTK](https://www.nltk.org/) tool kit for the processing using the literature corpus from the [Project Gothenburg](https://www.gutenberg.org/). 
