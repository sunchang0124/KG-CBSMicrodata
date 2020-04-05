# KG-CBSMicrodata
This repository is for the project from Knowledge Graph Course 2020. The goal of this project is to convert the descriptions of all CBS microdata sets into one knowledge graph with high-quality and comprehensive metadata so that the researchers can easily query the metadata, explore the relations among multiple datasets, and find the needed variables.

**Workflow**

1. Automatically download data description files (PDF)
2. Extract text from PDF files
3. Translate extracted text from Dutch to English
4. Extract key information from the text (English)
5. Find suitable vocabularies
6. Convert CSV to RDF using R2RML
7. Complete knowledge graph

![Workflow Diagram](https://github.com/sunchang0124/KG-CBSMicrodata/raw/master/CBSMicrodata.png)

**R2RML mapping**

Mapping file is in the mapping_cbs.ttl. 

** Knowledge Graph in GraphDB **

![Workflow Diagram](https://github.com/sunchang0124/KG-CBSMicrodata/raw/master/graphdb1.png)
