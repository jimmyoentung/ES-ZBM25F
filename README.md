# ES-ZBM25F
ElasticSearch 5.1.1 similarity BM25F Implementation based on Zaragoza, Craswell, Taylor, Saria, Robertson. 2004. Microsoft Cambridge at TREC 13: Web and Hard Tracks. In: Proceeding of the 2004 Text REtrieval Conference (TREC), vol 4. p 1.


## Config
Add the following to ES config (elasticsearch.yml) to enable groovy inline scripting language. Groovy is used as the painless has no access to the _index object which provide access to various index statistics such as tf
```
script.inline: true
```
