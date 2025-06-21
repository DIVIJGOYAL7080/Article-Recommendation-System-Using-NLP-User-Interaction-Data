# Article-Recommendation-System-Using-NLP-User-Interaction-Data
This project builds a content-based article recommendation engine using a real-world dataset from Kaggle's Deskdrop dataset. The system analyzes both the textual content (titles) of shared articles and the user interaction events (views, likes, bookmarks, etc.) to measure article popularity and similarity.

We use NLP (Natural Language Processing) with CountVectorizer to convert article titles into vector form and calculate cosine similarity between them. Based on this, the system recommends similar articles to users. Interaction metrics are used to filter out irrelevant or low-engagement content.
