#  Movie Recommendation System (Content-Based)

##  Overview
This project implements a **Content-Based Movie Recommendation System** using Natural Language Processing techniques. It recommends similar movies based on metadata such as genres, keywords, cast, and directors.

##  Machine Learning Approach
- Text preprocessing and feature engineering
- TF-IDF Vectorization
- Cosine Similarity for similarity measurement
- Fuzzy matching using difflib for user input handling

##  Workflow
Data Collection ➜ Preprocessing ➜ Feature Extraction ➜ Similarity Computation ➜ Recommendation Output

##  Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- NLP (TF-IDF)
- difflib

##  How to Run
1. Clone the repository
2. Open the notebook
3. Run all cells
4. Enter a movie name to get recommendations

##  Output
The system returns top similar movies based on cosine similarity score.

##  Future Improvements
- Add collaborative filtering
- Deploy as a web application
