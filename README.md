# WoS' Journal Citation Reports

## Description

This repository is responsible for scraping the web page related to the InCites Journal Citation Report (Web of Science).

## Required information

The raw data collected by the Jupyter Notebooks, which are contained into the folder "data_collection". To collect the data, it is necessary to have a registered user on the [Clarivate platform](https://clarivate.com) of the Web of Science. If you don't have it, create it from this [link](https://access.clarivate.com/register?app=jcr).

## Dataset features

The features of the resulting dataset are:
* journal_name: the name of a source/journal.
* issn: the ISSN of a source/journal.
* e_issn: the E-ISSN of a source/journal.
* category: the list of subject/study fields belonging to the scope of publication of a source/journal.
* edition: the edition or set of indexed journals that are being classified or evaluated.
* total_citations: the total number of citation of a source/journal.
* impact_factor_2023: the 2023 Journal Impact Factor (JIF) of a source/journal.
* jif_quartile: the quartile of JIF of a source/journal.
* jci_2023: the 2023 Journal Citation Indicator (JCI) of a source/journal.
* percent_oa_gold: the percentage of citable open-access items.

## Citation

Santos, Breno Santana. **Web Scraping of the Journal Citation Reports from Web of Science** [Internet]. Natal: Rio Grande do Norte, Brazil; 2023 Sep 12. Available from: https://github.com/breno-madruga/journal-citation-reports-wos.
