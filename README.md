To count the number of papers from PubMed reviewed in December 2025, I did the following. 

I viewed the shared Zotero collection called llm-bias-med. 

I exported the “All” folder associated with that step of review in the shared Zotero folder. 
Specifically, I exported them to csv files, and then I ran a python script to search for duplicates and tell me the deduplicated number. 
I also accounted for near duplicates and reviewed all the pairs of titles that got flagged as duplicates.

Note that there were some pairs of titles that were falsely flagged as duplicates, because one of them was the authors' reply.
I accounted for this in the code so that these pairs are not counted as duplicates.
