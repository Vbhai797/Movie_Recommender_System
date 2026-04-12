**Movie Recommender System**
A content-based Movie Recommender System built using Python and Machine Learning.
This application suggests movies similar to the one selected by the user based on movie features like genre, keywords, cast, and overview.

The project also includes a web interface built with Streamlit that allows users to interactively get movie recommendations.

🚀 Live Demo

🔗 Try the app here: https://movie-recommender-system-vbhai.onrender.com/
📌 Features
🎥 Recommend movies similar to a selected movie
📊 Content-based recommendation using cosine similarity
🖥️ Interactive web interface built with Streamlit
⚡ Fast recommendation generation
📂 Clean and modular project structure

🧠 How It Works

- The recommender system uses Content-Based Filtering:
- Movie dataset is processed and important features are extracted.
- Features are combined into a tags column.
- Text data is converted into vectors using CountVectorizer.
- When a user selects a movie, the system returns the most similar movies.

🛠️ Tech Stack
Python
Scikit-learn
Pickle
Streamlit

Libraries used:
pandas
numpy
scikit-learn
streamlit
pickle

📂 Project Structure
Movie_Recommender_System
│
├── app.py                # Streamlit web app
├── movies.pkl            # Processed movie dataset
├── movies_dict.pkl       # Movie dictionary
├── similarity.pkl        # Similarity matrix
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
⚙️ Installation

Clone the repository from GitHub:
git clone https://github.com/your-username/Movie_Recommender_System.git

Navigate to the project folder:
cd Movie_Recommender_System

Install dependencies:
pip install -r requirements.txt
▶️ Run the Application

Start the Streamlit app:
streamlit run app.py

The app will open in your browser at:
http://localhost:8501


📊 Dataset
The dataset used contains movie information such as:
Title
Genre
Cast
Keywords
Overview


👨‍💻 Author
Vivek Yadav
GitHub:
https://github.com/Vbhai797

⭐ If you like this project

Please consider starring the repository on GitHub ⭐
