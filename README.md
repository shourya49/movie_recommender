🎬 Content-Based Movie Recommender System
📜 Project Overview
This project is a Content-Based Movie Recommender System developed using the TMDB movie dataset. The system suggests relevant movies to users based on their preferences, such as a movie title they like. By analyzing various content features like title, overview, genres, keywords, and cast, the recommender identifies movies with similar characteristics. The project includes a user-friendly web interface built using Streamlit.<br>

🔧 Key Features
Content-Based Filtering: The system uses movie metadata (title, genres, overview, keywords, and cast) to compute similarity and recommend movies.<br>
Text Vectorization (Word-by-Word): Text features are processed by breaking them into words, assigning a numerical representation, and identifying word-based content similarity.<br>
Cosine Similarity: Used to measure similarity between movies based on their word vector representations.<br>
Streamlit Web Interface: Created an interactive website where users can input a movie title and receive movie recommendations.<br>
User Input: Users can search for a movie title, and the system will display a list of top similar movies.<br>
TMDB Dataset: Utilized TMDB's rich dataset, containing movie metadata such as genres, descriptions, and actors.<br>
🛠️ Tech Stack
Python<br>
Streamlit: For building an interactive web application<br>
Pandas: For data processing and cleaning<br>
Scikit-learn: For cosine similarity computation<br>
NumPy: For efficient numerical computations<br>
🚀 How It Works
The TMDB dataset is preprocessed to extract relevant features: title, overview, genres, keywords, and cast.<br>
Text features are broken into words (tokenized), and each word is vectorized for numerical representation.<br>
Cosine similarity is calculated to compare vectorized word-based representations and identify movies with the most similar content.<br>
The Streamlit web interface allows users to input a movie title and displays the top N most similar movies as output.<br>
🌐 Website Interface
Users can enter a movie title in the search bar.<br>
The application returns a list of movies similar to the selected title.<br>
Simple and intuitive design for seamless user experience.<br>
🖥️ Access the App
Run locally on:
http://localhost:8501<br>
Access on your network:
http://192.168.27.84:8501<br>
📊 Example Usage
Suppose the user inputs the movie title "Harry Potter and the Goblet of Fire":<br>

The system might return:<br>

Harry Potter and the Prisoner of Azkaban<br>
Harry Potter and the Order of the Phoenix<br>
Harry Potter and the Chamber of Secrets<br>
Harry Potter and the Philosopher's Stone<br>
Harry Potter and the Half-Blood Prince<br>
💾 Dataset
The dataset is sourced from the TMDB Movie Dataset, which includes movie metadata like titles, genres, keywords, and overviews.<br>

🖥️ Running the Project
To run the project locally:<br>

Install the required libraries:
<br>
pip install streamlit pandas scikit-learn numpy  
<br>
Run the Streamlit app:
<br>
streamlit run app.py  
<br>
Open the browser at:
<br>
Local access: http://localhost:8501
<br>
Network access: http://192.168.27.84:8501
<br>

