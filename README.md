# Cuisine-Recommendation-Yelp-Data
 Recommend top 3 cuisines for 100 customers based on their top 2 cuisines
 
 # Steps
 1. Read Yelp business and reviews data, merge after filtering out reviews less than 3 stars and businesses not in the Restuarants / Food / Nightlife categories
 2. Categorize by different cuisines and write all the reviews to .txt files 
 3. Construct a dataframe where each row represents a document (all the text reviews) for one cuisine
 4. Construct a TfIdf vector (document term matrix) of all the documents in the corpus 
 5. Find cosine similarity between all pairs of cuisines based on the TfIdf vector 
 6. Read the order data, massage to find top cuisine for each of the 100 customers, also massage to add the list of cuisines they have ordered from
 7. For each customer, find the top 3 cuisines similar to their top cuisine (excluding the ones they have already ordered from)
