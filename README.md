# Entity-Resolution-Amazon-Google-Database-Match
In this project, Entity Resolution (ER), Text Analytics, and Machine Learning techniques are used to optimize a product matching system between Google and Amazon product database.

## About Project
In this project, I applied TF-IDF to clean and tokenize and  vectorized the text data. I Leveraged **Blocking algorithms** to optimize the product match system between Google and Amazon database, achieved **99.96%** Reduction Ratio compared to exhaustive matching pairs. To evaluate the matching system, I computed the similarity between records in candidate pairs with various similarity metrics (Cosine similarity,  normalized Levenshtein similarity, etc.), and conducted Feature Engineering with the similarity metrics, developed Machine Learning models (Gradient Boosting, Decision Tree, Random Forest) to predict duplicates pairs (matching pairs).

## Modeling
* Entity Resolution
* Information Retrieval
* Blocking
* TF-IDF
* ML: Gradient Boosting, Decision Tree, Random Forest

## Dependencies:
* scikit-learn
* NLTK
* Levenshtei

Entity Resolution (ER) reference: <br>
Kejriwal, M., Knoblock, C. A., & Szekely, P. (2021). Knowledge Graphs: Fundamentals, Techniques, and Applications (Adaptive Computation and Machine Learning series). The MIT Press.
Retrieved from [link](https://mitpress.mit.edu/9780262045094/knowledge-graphs/).




