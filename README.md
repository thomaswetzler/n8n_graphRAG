# n8n_graphRAG
GraphRAG with Neo4j and Qdrant on n8n

In this repository, I test n8n — an open-source automation tool marketed as “no-code” — to implement a GraphRAG pipeline with Neo4j and Qdrant. I walk through the challenges of idempotent workflows, and the limitations of n8n’s built-in nodes. While workarounds exist, they often require coding, undermining the no-code promise. 

There are four n8n workflows existing. Three to build up the GraphRAG. The framework calls the other two. 
- framework_workflow
- neo4j_workflow
- qdrant_workflow

and one with a very simple query workflow:
- query_workflow 

A description can be found on [medium](https://medium.com/@linos2/graphrag-with-neo4j-and-qdrant-on-n8n-8fa799a4a24d). 
