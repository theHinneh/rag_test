# Building A RAG System

## Introduction

This document describes the steps to build Retrieval Augmented Generation (RAG) system using Hugging Face's transformers library. The RAG system is a combination of a retriever and a generator. The retriever is responsible for retrieving relevant passages from a large corpus of text, and the generator is responsible for generating the answer based on the retrieved passages. The RAG system is trained end-to-end using a combination of supervised and reinforcement learning.
The implementation in this sample uses mongoDB as the database to store the corpus of text. The corpus of text is stored in the `movie_collection_2` collection in the `movies` database. The corpus of text is stored as a list of dictionaries.

## Steps to build the RAG system

1. Install and import the required libraries
2. download the dataset
3. Preprocess the dataset
4. Generate the embeddings for the dataset
5. Setup database
6. Store the embeddings in the database
7. Build the RAG system
