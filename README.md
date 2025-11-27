Description

Ce projet implémente un chatbot basé sur un modèle de langage (LLM) utilisant une approche RAG (retrieval-augmented generation).
Il permet de répondre à des questions en s’appuyant sur un corpus de documents stocké dans une base de données PostgreSQL avec pgvector pour la recherche par similarité.

Le modèle par défaut est ultra-léger (flan-t5-small) afin de faciliter l’exécution locale sans GPU puissant.