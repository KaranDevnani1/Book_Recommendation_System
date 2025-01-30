# Book Recommendation System

## 📌 Overview
This project is a **Book Recommendation System** built using Flask and machine learning. It provides book recommendations based on user input and displays popular books.

## ✨ Features
- Displays popular books based on ratings and votes.
- Recommends books similar to user input.
- Uses a trained similarity model to find recommendations.

## 🛠 Technologies Used
- **Python** (Flask, NumPy, Pandas, Pickle)
- **Machine Learning** (Collaborative Filtering, Similarity Scores)

## 🚀 How to Run the Project

### Prerequisites
Ensure you have:
- **Python 3.x** installed
- Flask and required dependencies

### Steps to Run:
1. Clone the repository:
   ```bash
   git clone <your-repo-link>
   cd <your-repo-folder>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask app:
   ```bash
   python app.py
   ```

## 📊 How It Works
- The system loads precomputed similarity scores from `similarity_scores.pkl`.
- Users input a book title, and the system finds similar books.
- Recommendations are displayed on the web interface.

## 🎯 Future Improvements
- Add a user-based recommendation system.
- Implement a database instead of pickle files.
- Deploy the app on a cloud platform.

## 📜 License
This project is for educational purposes. Feel free to modify and use it as needed.
