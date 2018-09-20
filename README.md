# Legal-Sentence-Classification-Datasets-and-Models
This project is a collection of two different datasets constituting legal sentences from the tenancy law of the German civil law as well as legal word2vec models.

If you use the data and publish please let us know. We may provide a paper to cite in the neat future.

## License
All three corpora are released under the CC BY-SA 3.0 license.

## Content

### Datasets

#### Statutory Texts
601 sentences from the tenancy law of the German Civil Code (BGB, §535-§597).

The dataset is annotated sentency-by-sentence according to three different taxonomies (3 semantic types, 6 semantic types, and 9 semantic types).

#### Rental Agreements
312 sentences, classified according to a semantic type system consisting of 9 different classes, from German rental agreements.

### Word2Vec Models

#### JRCAcquis Corpus
A word2vec model trained on the German JRCAcquis corpus<sup>[1](#citation1)</sup> in 10 iterations using 300 dimension and a window size of 5. The corpus was pre-processed by the following steps:

1. Removing line breaks
1. Removing duplicated whitespaces
1. Replacing German umlauts
1. Spelling numbers
1. Removing punctuation
1. Removing token with less than 3 characters


Afterwards the corpus constituted 33.686.085 token.

#### German Fiscal Law Judgments
A word2vec model trained on a corpus of judgments from the German fiscal law in 10 iterations using 300 dimension and a window size of 5. The corpus was pre-processed by the following steps:

1. Removing line breaks
1. Removing duplicated whitespaces
1. Replacing German umlauts
1. Spelling numbers
1. Removing punctuation
1. Removing token with less than 3 characters


Afterwards the corpus constituted 33.686.085 token.

## Contact Information
If you have any questions, please contact:

[Ingo Glaser](https://wwwmatthes.in.tum.de/pages/5uj7ccpr2wvr/Ingo-Glaser) (Technical University of Munich) ingo.glaser@tum.de


<a name="citation1">1.</a>: Steinberger, R., Pouliquen, B., Widiger, A., Ignat, C., Erjavec, T., Tufis, D., & Varga, D. (2006). The JRC-Acquis: A multilingual aligned parallel corpus with 20+ languages. arXiv preprint cs/0609058
