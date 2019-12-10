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
- Following are the columns in each csv file :
  1. Query : query text for the given task
  2. URL :  Link to the document retrieved by the query
  3. score : Calculated Query Liklihood Score from Baseline Model
  4. Ranking : Relevance score by Humans
  5. QL_rank : Rank of the document estimated by the model using score
  6. DCG : Discounted Cumulative Gain for the retrieved documents
  7. NDCG : Normalized Discounted Cumulative Gain 