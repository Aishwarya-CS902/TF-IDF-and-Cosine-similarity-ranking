# Algorithms for Information Retrieval and Intelligence Web (AIRIW) Project

## Document-Retrieval-using-TF-IDF-Weighted-Rank-and-TF-IDF-Cosine-Similarity


### Overview:
This project implements document retrieval techniques using TF-IDF (Term Frequency-Inverse Document Frequency) weighted rank and TF-IDF cosine similarity. It involves preprocessing text data, calculating document frequencies (DF), and computing TF-IDF scores for both document bodies and titles. The project evaluates document relevance using TF-IDF weighted rank and cosine similarity, providing rankings based on the input query.

### Procedure:

__Combining all folders:__ The files are collected from multiple folders and integrated for unified processing.

__Collecting file names and titles:__ The metadata about documents, including filenames and titles is printed.

__Preprocessing:__ The text data is cleaned and prepared for analysis, including tokenization and normalization.

__Extracting Data:__ Relevant information is extracted from documents for further analysis.

__Calculating DF for all words:__ The Document Frequency (DF) is calculated to understand word distribution across documents.

__Calculating TF-IDF for Body:__ The TF-IDF scores are computed for document bodies, incorporating title weights.

__Calculating TF-IDF for Title:__ Then, the TF-IDF scores are computed specifically for document titles.

__Merging TF-IDF according to weights:__ The TF-IDF scores from body and title are integrated, by applying appropriate weighting.

__TF-IDF Matching Score Ranking:__ The documents are ranked based on TF-IDF matching scores relative to the input query.

__TF-IDF Cosine Similarity Ranking:__ Cosine similarity is utilized to rank documents based on similarity to the input query.

### Inferences:
Both cosine similarity ranking and TF-IDF ranking return an array of document IDs in decreasing order of relevance. The first element of the array typically matches the given query, indicating its high relevance.

### Example Observation:
The output document ID for both the ranking metrics is 328, which matches the document ID of the input query (328), demonstrating high relevance.

### Team members:
- Aishwarya Rajkumar - PES2UG21CS902
- Shreya Joshi - PES2UG21CS501
