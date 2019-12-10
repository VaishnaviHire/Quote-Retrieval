# Quote-Retrieval
Quotes and opinions of a particular person, as attributed to them in news articles, social media, books, etc.

## Run instructions:

1. Make sure you have `Python 3.7` installed
2. Run `pip install -r requirements.txt` to install all requirements locally
3. Run `python main.py` for each question

## Results:

- Output is written in files , which are stored in `Results` folder.
- Every file in this directory corresponds to a single query. 
- The csv contains query, document retrieved, DCG, NDCG scores , human relevance score and model rankings. 