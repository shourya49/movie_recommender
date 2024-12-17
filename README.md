🎬 Content-Based Movie Recommender System
📜 Project Overview
This project is a Content-Based Movie Recommender System developed using the TMDB movie dataset. The system suggests relevant movies to users based on their preferences, such as a movie title they like. By analyzing various content features like title, overview, genres, keywords, and cast, the recommender identifies movies with similar characteristics. The project includes a user-friendly web interface built using Streamlit.

🔧 Key Features
Content-Based Filtering: The system uses movie metadata (title, genres, overview, keywords, and cast) to compute similarity and recommend movies.
Text Vectorization (Word-by-Word): Text features are processed by breaking them into words, assigning a numerical representation, and identifying word-based content similarity.
Cosine Similarity: Used to measure similarity between movies based on their word vector representations.
Streamlit Web Interface: Created an interactive website where users can input a movie title and receive movie recommendations.
User Input: Users can search for a movie title, and the system will display a list of top similar movies.
TMDB Dataset: Utilized TMDB's rich dataset, containing movie metadata such as genres, descriptions, and actors.
🛠️ Tech Stack
Python
Streamlit: For building an interactive web application
Pandas: For data processing and cleaning
Scikit-learn: For cosine similarity computation
NumPy: For efficient numerical computations
🚀 How It Works
The TMDB dataset is preprocessed to extract relevant features: title, overview, genres, keywords, and cast.
Text features are broken into words (tokenized), and each word is vectorized for numerical representation.
Cosine similarity is calculated to compare vectorized word-based representations and identify movies with the most similar content.
The Streamlit web interface allows users to input a movie title and displays the top N most similar movies as output.
🌐 Website Interface
Users can enter a movie title in the search bar.
The application returns a list of movies similar to the selected title.
Simple and intuitive design for seamless user experience.
🖥️ Access the App
Run locally on:
http://localhost:8501
Access on your network:
http://192.168.27.84:8501
📊 Example Usage
Suppose the user inputs the movie title "Harry Potter and the Goblet of Fire":

The system might return:

Harry Potter and the Prisoner of Azkaban
Harry Potter and the Order of the Phoenix
Harry Potter and the Chamber of Secrets
Harry Potter and the Philosopher's Stone
Harry Potter and the Half-Blood Prince
💾 Dataset
The dataset is sourced from the TMDB Movie Dataset, which includes movie metadata like titles, genres, keywords, and overviews.

🖥️ Running the Project
To run the project locally:

Install the required libraries:
bash
Copy code
pip install streamlit pandas scikit-learn numpy  
Run the Streamlit app:
bash
Copy code
streamlit run app.py  
Open the browser at:
Local access: http://localhost:8501
Network access: http://192.168.27.84:8501
