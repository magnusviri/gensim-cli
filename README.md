## gensim-cli

Interactive simple command line tool to work with the [Gensim](https://github.com/RaRe-Technologies/gensim) library.

## Install and usage

```
pip install --upgrade gensim
git clone https://github.com/magnusviri/gensim-cli.git
cd gensim-cli
./gensim-cli
```

Models will be stored in ~/gensim-data

## Example Usage

This is what it does.

```
Pick a model
1. __testing_word2vec-matrix-synopsis
2. conceptnet-numberbatch-17-06-300
3. fasttext-wiki-news-subwords-300
4. glove-twitter-100
5. glove-twitter-200
6. glove-twitter-25
7. glove-twitter-50
8. glove-wiki-gigaword-100
9. glove-wiki-gigaword-200
10. glove-wiki-gigaword-300
11. glove-wiki-gigaword-50
12. word2vec-google-news-300
13. word2vec-ruscorpora-300
Enter a number, or e[x]it/[q]uit: 12
word2vec-google-news-300 (3000000 records)
Pre-trained vectors trained on a part of the Google News dataset (about 100 billion words). The model contains 300-dimensional vectors for 3 million words and phrases. The phrases were obtained using a simple data-driven approach described in 'Distributed Representations of Words and Phrases and their Compositionality' (https://code.google.com/archive/p/word2vec/).
Choose this model [y/n]? y
[==================================================] 100.0% 1662.8/1662.8MB downloaded
Model loaded in 308.6200 seconds.
Current model: word2vec-google-news-300
1. Change Model
2. Distance
3. Most Similar
4. Most Similar Cosmul
5. Doesnt Match
6. Closer Than
Enter a number, or e[x]it/[q]uit: 2
2 words (blank to return): red blue
0.27748262882232666
2 words (blank to return):
Current model: word2vec-google-news-300
1. Change Model
2. Distance
3. Most Similar
4. Most Similar Cosmul
5. Doesnt Match
6. Closer Than
Enter a number, or e[x]it/[q]uit: 3
Postivie words (blank to return): king woman
Negative words (blank to return): man
[('queen', 0.7118192911148071),
 ('monarch', 0.6189674735069275),
 ('princess', 0.5902431011199951),
 ('crown_prince', 0.5499460697174072),
 ('prince', 0.5377321243286133),
 ('kings', 0.5236844420433044),
 ('Queen_Consort', 0.5235945582389832),
 ('queens', 0.5181134343147278),
 ('sultan', 0.5098593235015869),
 ('monarchy', 0.5087411403656006)]
Postivie words (blank to return):
Negative words (blank to return):
Current model: word2vec-google-news-300
1. Change Model
2. Distance
3. Most Similar
4. Most Similar Cosmul
5. Doesnt Match
6. Closer Than
Enter a number, or e[x]it/[q]uit: 5
List of words (blank to return): king queen man woman prince dog
'dog'
List of words (blank to return):
```