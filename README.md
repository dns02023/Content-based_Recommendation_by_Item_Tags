# Content-based_Recommendation_by_Item_Tags

In this project, there are 3 ways to compute similarity of items(restaurant). 

1. Count Vectorizer : Simply get Count Vectors of each items' tags => Compute cosine similarity of each items
2. TF-IDF : Get TF-IDF matrix of items' tags => Compute cosine similarity of each itmes
3. Rake : Extracting keywords of each items' tags => Get Count Vectors of each items' tags => Compute cosine similarity of each items  

Based on similarity, content-based recommendation recommends items which are similar to target item.  
Data from Korea University KOREAPAS sofo
