# LEGAL-DOCUMENT-RETRIEVAL-FOR-SOICT-HACKATHON-2024


This project was developed for the **SoICT Hackathon 2024 - Legal Document Retrieval** competition. The challenge focused on retrieving relevant Vietnamese legal documents for a given set of queries, using advanced natural language processing (NLP) techniques.

## Overview  
The goal of the project was to fine-tune the **BAAI/bge-m3** model to optimize retrieval accuracy for Vietnamese legal texts. The approach involved creating a triplet dataset for training, fine-tuning both the embedder and reranker components, and evaluating the model on the competition's Public Test Data.

## Key Features  
- **Fine-Tuned Model:** Improved the **BAAI/bge-m3** model's performance using a custom triplet dataset derived from labeled training data (query-document pairs).  
- **Advanced Retrieval Techniques:** Enhanced both dense and re-ranking stages of the document retrieval pipeline to ensure high accuracy.  
- **Evaluation Success:** Ranked **Top 16** on the Public Test leaderboard based on the **MRR@10** metric.
