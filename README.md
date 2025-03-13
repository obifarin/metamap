The goal of this work is to map the landscape of metabolomics research using natural language processing. Paper:  

## Colab (Jupyter) Notebooks

Contains all jupyter notebooks for the project. 

`01-publication-analytics.ipynb`

Contains publication analytics such as publication per year, publication rate of change, top published journals, frequently used words, and abstract distribution.

`02-publication-embeddings.ipynb`

Contains XML file conversion to pandas dataframe, classification of publications abstracts into groups, computations of embeddings with PubMedBERT and processing of the embeddings.

`03-dimensionality-reduction-evals.ipynb`

Contains evaluation of dimensionality reductions of embeddings.

`04-research-field-embeddings.ipynb`

Contains UMAP and t-SNE embeddings plotted with research fields. Also included are some research field trends, such as those in plant sciences, analytical chemistry, toxicology, and environmental sciences.

`05-temporal-evolution.ipynb`

Contains temporal evolution of publications.
`06-publication-metadata.ipynb`

Contains analysis of publication metadata such as p-values, reported sample sizes, keyword highlights, abstracts, and journal title lengths, and number of authors.

`07-keyword-trends.ipynb`

Contains detailed analysis of some scientific keyword trends relating to disease and data analysis.

`08-topic-modelling-bertopic.ipynb`

Contains topic modeling with BERTopic using OpenAI GPT-4o-mini and pre-computed PubMedBERT and tSNE embeddings.

`09-topic-modelling-results.ipynb`

Contains some topic modeling (unpublished) results.

## Topic Model

Saved BERTopic topic models.

## File

embeddings_full_tSNE_uMAP_DDMONYEAR.h5

This is the complete embedding for the dataset: 1) It contains PubMed related datasets such as PMID, title, abstract, language, journal_title, pub_year, and authors. 2) The full embeddings (768) generated from PubMedBERT. 3) In addition to uMAP and tSNE embeddings. This will be the go to file to load. 
