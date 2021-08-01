# Data Mining And Text Analysis

For  both  problems,  the  dataset required  extensively cleaning and pre-processing before data mining techniques could be applied and 
knowledge gained. Importing, NaN removal,  data-type casting, parsing dictionaries, merging, and eliminating attributes were all processes carried
out.

-------------------------
### Problem 1 - 
-------------------------
The first problem  was to design and build a recommendation engine that takes a user’s ID and returns top 3 ranked movies to watch next.

A collaborative filtering approach  was decided  upon  when  designing a recommendation  engine 
due to  its accuracy and scalability when working  with user-item  sparse matrixes. The SVD 
algorithm  was used to  reduce  dimensionality and computational expense whilst maintaining a high 
level of prediction  accuracy.

Libraries used: Surprise


-------------------------
### Problem 2 - 
-------------------------
The second problem was to develop a data mining technique that explores the relationship between a movie’s keywords and its categorized genre 
using search engine information retrieval methods.

Each movie  was crawled, storing the keywords as documents before indexing into a corpus of documents for each genre. 
Natural  Language Processing techniques were  used to  tokenize  and reduce  the document-term  matrix size. 
Keywords  were  vectorised and used as search queries and cosine similarity scores were  calculated 
to establish the top  ranking genre. To evaluate the  strength of the  relationship between  the 
keyword  and their  associated genres, top ranking genre was compared  to its original genre  and 
matches/misses were counted.  48.61%  of movies returned  a top  genre search match,  indicating a 
strong relationship between  genres  and keywords. 

Libraries used: NumPy, Pandas, SKLearn, Regex, Matplotlib and NLTK
