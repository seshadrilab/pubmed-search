# Searching PubMed automatically

This notebook (intended to be run on Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seshadrilab/pubmed-search/blob/main/pubmed_search.ipynb)) takes an excel file of authors and their institutions and searches PubMed for tuberculosis-related papers from those authors published during a user-specified date range. Output is:
* a semicolon-separated list of PubMed IDs, which can be pasted directly into the PubMed search box to get a page listing those papers
* a CSV file (`SEATRAC_pubmed_citation_counts.csv`) with citation counts and other metadata (year, title, relative citation ratio) for each paper, pulled from the NIH iCite API

### More info:

* PubMed API (NCBI Entrez E-utilities) help: https://www.ncbi.nlm.nih.gov/books/NBK25497/#chapter2.Introduction
* More help: https://pubmed.ncbi.nlm.nih.gov/help/
* List of PubMed "tags": https://www.ncbi.nlm.nih.gov/pmc/about/userguide/
