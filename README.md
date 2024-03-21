# Funktio AI Samples (Fork)

This repository is a fork of Funktio AI Samples and contains several demonstrations and tools related to web scraping, knowledge graph construction, and model evaluation.

## Contents
scraping-demo: A demonstration of web scraping techniques.

knowledge-graph-demo:

- A Jupyter notebook for creating Neo4j Cypher queries to construct a knowledge graph based on provided documents.

- A Streamlit app for querying data from the knowledge graph.

trulens-eval-demo: Tools for evaluating machine learning models.

## Usage
To use the demonstrations in this repository, follow these steps:

- Create a Neo4j instance: Set up a Neo4j database instance to store and query the knowledge graph.
- Open the notebook: Navigate to the knowledge-graph-demo folder and open the Jupyter notebook.
- Configure environment variables: Set up the necessary environment variables for the model and the Neo4j connection.
- Customize prompts: Modify the prompts in the notebook as needed to fit your specific use case.
- Run the notebook: Execute the cells in the notebook to generate Cypher queries and populate the Neo4j database.
- View results: Use a Neo4j client to visualize and query the constructed knowledge graph.