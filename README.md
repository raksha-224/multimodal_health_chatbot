# multimodal_health_chatbot
## Overview
A multimodal Retrieval-Augmented Generation (RAG) system that answers questions from healthcare PDF reports by combining:
Text extraction from PDFs
Figure and table reference detection
Semantic retrieval using Sentence Transformers
Keyword retrieval using BM25
Hybrid search fusion
Gemini-powered answer generation
The system automatically identifies relevant document sections and associated figures/tables before generating grounded answers.

## Features
Extracts text, images, tables, and captions from PDF reports
Detects references such as:
Figure 1.1
Figure 2.5
Table 3.2
Chunks large documents for efficient retrieval
Hybrid retrieval:
Dense semantic search (Sentence Transformers)
Sparse lexical search (BM25)
Automatic figure reference linking
Generates contextual answers using Gemini
Produces competition-style submission CSV output


