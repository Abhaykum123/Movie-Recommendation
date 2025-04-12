🎬 Movie Recommendation System
A content-based movie recommendation system built using the TMDB 5000 Movie Dataset. This project leverages natural language processing and machine learning techniques to recommend similar movies based on user-selected titles.

--------------------------------------------------------------------------------------------------------------------------
📂 Dataset
*Name: TMDB 5000 Movie Dataset

*Source: Kaggle

*Files Used:

*tmdb_5000_movies.csv

*tmdb_5000_credits.csv

-----------------------------------------------------------------------------------------------------------------------
📌 Features
Recommend top 5 similar movies based on selected movie.

Text-based content filtering using movie features such as genres, keywords, overview, cast, and crew.

Cosine similarity metric to calculate similarity scores.

Clean, interactive interface via Streamlit (if applicable — adjust if your project doesn’t have this).

-----------------------------------------------------------------------------------------------------------------------

📊 Technologies Used
Python 3

Pandas

NumPy

Scikit-learn

NLP (Natural Language Processing)

Streamlit

Pickle (for model serialization)

-----------------------------------------------------------------------------------------------------------------------

📑 Project Structure
kotlin
Copy code
├── data/
│   ├── tmdb_5000_movies.csv
│   └── tmdb_5000_credits.csv
├── app.py
├── Movie Recommender System.ipynb
├── movie_dict.pkl
├──similarity.pkl README.md
└── README.md

-----------------------------------------------------------------------------------------------------------------------

🚀 How to Run
Clone the repository

bash
Copy code
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system
Install dependencies

bash
Copy code
pip install -r requirements.txt
Run the app

bash
Copy code
streamlit run app.py

-----------------------------------------------------------------------------------------------------------------------

📝 Methodology
Data Preprocessing: Merged movie and credits datasets. Cleaned and processed textual data.

Feature Engineering: Combined important text features like genres, cast, crew, overview, and keywords into a single column.

Text Vectorization: Converted combined text into numerical vectors using CountVectorizer.

Similarity Calculation: Applied Cosine Similarity to find similar movies.

Recommendation: Displayed the top 5 movies based on similarity scores.

-----------------------------------------------------------------------------------------------------------------------

🎥 Example Output
![Screenshot 2025-04-12 145147](https://github.com/user-attachments/assets/3db80777-2851-4667-9cf5-2aea40d6a73e)

-----------------------------------------------------------------------------------------------------------------------

📌 Future Improvements
Deploy on Heroku / Streamlit Cloud.

Integrate TMDB API for dynamic, real-time data.

Add user-based collaborative filtering.

Improve the front-end interface.

-----------------------------------------------------------------------------------------------------------------------

📜 License
This project is licensed under the MIT License.

-----------------------------------------------------------------------------------------------------------------------

🙌 Acknowledgements
TMDB 5000 Movie Dataset on Kaggle

Scikit-learn Documentation

Streamlit (if applicable)
