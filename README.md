The goal of this work is to map the landscape of metabolomics research using natural language processing. 

Preprint: https://pubs.acs.org/doi/10.1021/acs.analchem.5c01672
Try out the accompany app: https://metascape.streamlit.app/

## Colab (Jupyter) Notebooks

Contains all jupyter notebooks for the project. 

`01-publication-analytics.ipynb`: Contains publication analytics such as publication per year, publication rate of change, top published journals, frequently used words, and abstract distribution.

`02-publication-embeddings.ipynb`: Contains XML file conversion to pandas dataframe, classification of publications abstracts into groups, computations of embeddings with PubMedBERT and processing of the embeddings.

`03-dimensionality-reduction-evals.ipynb`: Contains evaluation of dimensionality reductions of embeddings.

`04-research-field-embeddings.ipynb`: Contains UMAP and t-SNE embeddings plotted with research fields. Also included are some research field trends, such as those in plant sciences, analytical chemistry, toxicology, and environmental sciences.

`05-temporal-evolution.ipynb`: Contains temporal evolution of publications.

`06-publication-metadata.ipynb`: Contains analysis of publication metadata such as p-values, reported sample sizes, keyword highlights, abstracts, and journal title lengths, and number of authors.

`07-keyword-trends.ipynb`: Contains detailed analysis of some scientific keyword trends relating to disease and data analysis.

`08-topic-modelling-bertopic.ipynb`: Contains topic modeling with BERTopic using OpenAI GPT-4o-mini and pre-computed PubMedBERT and tSNE embeddings.

`09-topic-modelling-results.ipynb`: Contains some topic modeling (unpublished) results.

`10-topic-coherence-evaluation.ipynb`: Contains topic coherence evaluation C_v and C_npmi

## Topic Model

Saved BERTopic topic models.

## Files

Retrieve from Bifarin, O., & Yelluru, V. (2025). Metabolomics Publications in PubMed: Embeddings and Associated Datasets [Data set]. Zenodo. https://doi.org/10.5281/zenodo.15020144

