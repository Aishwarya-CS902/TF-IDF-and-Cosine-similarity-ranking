# Algorithms for Information Retrieval and Intelligence Web (AIRIW) Project

## Document-Retrieval-using-TF-IDF-Weighted-Rank-and-TF-IDF-Cosine-Similarity


### Overview:
This project implements document retrieval techniques using TF-IDF (Term Frequency-Inverse Document Frequency) weighted rank and TF-IDF cosine similarity. It involves preprocessing text data, calculating document frequencies (DF), and computing TF-IDF scores for both document bodies and titles. The project evaluates document relevance using TF-IDF weighted rank and cosine similarity, providing rankings based on the input query.

### Features:

Combining all folders: Collects and integrates files from multiple folders for unified processing.

Collecting file names and titles: Gathers metadata about documents, including filenames and titles.

Preprocessing: Cleans and prepares text data for analysis, including tokenization and normalization.

Extracting Data: Extracts relevant information from documents for further analysis.

Calculating DF for all words: Computes Document Frequency (DF) to understand word distribution across documents.

Calculating TF-IDF for Body: Computes TF-IDF scores for document bodies, incorporating title weights.

Calculating TF-IDF for Title: Computes TF-IDF scores specifically for document titles.

Merging TF-IDF according to weights: Integrates TF-IDF scores from body and title, applying appropriate weighting.

TF-IDF Matching Score Ranking: Ranks documents based on TF-IDF matching scores relative to the input query.

TF-IDF Cosine Similarity Ranking: Utilizes cosine similarity to rank documents based on similarity to the input query.

Vectorising tf-idf: Represents TF-IDF scores in vector form for cosine similarity calculations.

### Inferences:
Both cosine similarity ranking and TF-IDF ranking return an array of document IDs in decreasing order of relevance. The first element of the array typically matches the given query, indicating its high relevance.

### Example Observation:
The output document ID 328 matches the document ID of the input query (328), demonstrating high relevance.

### Team members:
- Aishwarya Rajkumar - PES2UG21CS902
- Shreya Joshi - PES2UG21CS501
