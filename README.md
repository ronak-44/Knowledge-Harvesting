# Knowledge Harvesting (CKIDS 2022 DataFest)


## Goal 
* The project focused on developing a Knowledge Harvesting subsystem, specifically targeting the extraction of structured knowledge from GitHub READMEs.
* The ultimate aim was to generate question-answer pairs for a dialogue model.

## Approach 

* Crawling and processing the data - Used web scraping libraries to scrap the README page to get the raw data.
* The raw data was processed and information was extracted in the form of key/value pairs.
* Train a QA specific information extraction model that is capable of generating relevant answers for the given question from the corpus.
