This is a repository for Web Semantics Class in EURECOM Fall 2024. The goal of this project is to extract information from multilingual textual documents about cycling and create a knowledge graph (KG) using the extracted entities and relations. The KG will be compatible with a cycling ontology and queries will be written in SPARQL to retrieve specific information from the KG. The project will be implemented using Jupyter Notebook and the following steps will be followed:

- Collect multilingual textual documents about cycling.
- Pre-process the documents to get clean text files.
- Run named entity recognition (NER) on the documents to extract named entities of the type Person, Organization and Location using spaCy and LLMs.
- Run co-reference resolution on the input text using spaCy.
- Disambiguate the entities with Wikidata using OpenTapioca and LLMs.
- Run relation extraction using Stanford OpenIE and LLMs.
- Implement some mappings between the entity types and relations returned with the cycling ontology you developed during the Assignment 1 in order to create a knowledge graph of the domain represented in RDF.
- Load the data in the Corese engine as you did for the Assignment 2 with your cycling ontology and the knowledge graph built in the previous step and write some SPARQL queries to retrieve specific information from the KG.
