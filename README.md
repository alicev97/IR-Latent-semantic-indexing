# IR-Latent-semantic-indexing

Repository for the project of the course "Information Retrieval" of the master degree "Data Science and Scientific Computing" @UniTS.

For the project I needed to implement the following tasks:

- Write an IR system that uses latent semantic indexing to answer queries.
- The system must accept free-form text queries.
- Evaluate the system on a set of queries…
- …and try to use different dimensions for the dimensionality reduction.



## Data

Two different datasets are used.

The fist one, used for the initial building of the system, is contained in the [booksummaries folder](booksummaries). The [booksummaries.txt file](booksummaries/booksummaries.txt) is a collection of 16,559 book plot summaries extracted from Wikipedia, along with aligned metadata from Freebase, including book author, title, and genre.

The second dataset, used for the evaluation phase, is contained in the [cranfield folder](cranfield) is divided into three files:
- [cran.all.1400](cranfield/cran.all.1400) contains the Cranfield collection, formed by 1398 abstracts of aerodynamics journal articles, each of them is composed by an index, a title and a text.
- [cran.qry](cranfield/cran.qry) contains a set of 225 queries, composed by an index and a text.
- [crnqrel](cranfield/cranqrel) contains an exhaustive relevance judgments of all (query, document) pairs.