# DL Intern Tasks

This repository contains assignments for a deep learning internship, organized into two main folders: `assignment1` and `assignment2`.

---

## Folder Structure

requirements.txt

assignment1/

    scored_posts.csv
    
    sentiment_model.pkl
    
    sentiment_scoring.ipynb
    
    data/
        comments.csv
        
        engagement.csv

assignment2/

    recommendation_system.ipynb
    
    data/
    
        users.csv

## Setup

1. **Install dependencies**  
   Run the following command to install required Python packages:

   ```sh
   pip install -r requirements.txt
   ```

2. **Jupyter Notebook**  
   Launch Jupyter Notebook to work with the assignment notebooks:

   ```sh
   jupyter notebook
   ```

---

## Assignment 1: Sentiment Scoring

- **File:** [`assignment1/sentiment_scoring.ipynb`](assignment1/sentiment_scoring.ipynb)
- **Description:**  
  - Trains a sentiment analysis model on comment data.
  - Scores comments and posts based on sentiment and engagement.
  - Outputs results to [`scored_posts.csv`](assignment1/scored_posts.csv).

- **Data:**  
  - [`data/comments.csv`](assignment1/data/comments.csv): Raw comments.
  - [`data/engagement.csv`](assignment1/data/engagement.csv): Engagement metrics.

---

## Assignment 2: Recommendation System

- **File:** [`assignment2/recommendation_system.ipynb`](assignment2/recommendation_system.ipynb)
- **Description:**  
  - Builds a recommendation system using the scored posts from Assignment 1.
  - Evaluates recommendations using metrics like Precision@K and NDCG@K.

- **Data:**  
  - [`data/users.csv`](assignment2/data/users.csv): User profiles and preferences.

---

## Notes

- All data files are in CSV format.
- Notebooks are self-contained and can be run independently.
- Outputs (such as models and scored CSVs) are saved in their respective assignment folders.

---

## Requirements

See [`requirements.txt`](requirements.txt) for the full list of dependencies.

---

## Author
