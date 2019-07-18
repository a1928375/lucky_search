# lucky_search

We have implemented a page ranking algorithm, but didn't finish the final step of using it to improve our search results. For this question, you will use the page rankings to produce the best output for a given query. Define a procedure, lucky_search, that takes as input an index, a ranks dictionary (the result of compute_ranks), and a keyword, and returns the one URL most likely to be the best site for that keyword. If the keyword does not appear in the index, lucky_search should return None.
