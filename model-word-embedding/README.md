# Indonesian Pre-Trained Word Embedding (Word2Vec & FastText)

## Dataset
1. ID Wiki = 462.462 articles from Indonesia Wikipedia Dunmp (https://dumps.wikimedia.org/)
2. ID Tweet = 

## Parameter
- EMBEDDING_SIZE = 300
- WINDOW_SIZE = 5
- NUM_OF_EPOCH = 10
- TRAINING = SKIP_GRAM
- NEGATIVE_SAMPLING = True
- HIERARCHICAL_SOFTMAX = False

## Usage Example
```
!pip install gensim

WORD_EMBEDDING_PATH = 'idwiki-word2vec/idwiki-word2vec-300.wordvectors'
word2vec = KeyedVectors.load(WORD_EMBEDDING_PATH,  mmap='r')

vocabulary = word2vec.wv.vocab        # gensim 3
vocabulary = word2vec.index_to_key    # gensim 4

VOCAB_SIZE = len(vocabulary)
EMBEDDING_SIZE = word2vec.vector_size
```

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
