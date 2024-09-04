# Movie Recommendation System

## Overview
This project is a Movie Recommendation System that suggests movies to users based on their preferences. The system leverages various machine learning algorithms and techniques to provide accurate and personalized recommendations.

## Features
- **Content-Based Recommendation Engine**: Suggests movies similar to those the user has liked in the past by analyzing movie metadata such as genres, directors, and cast.
  
- **Cosine Similarity**: Used in the content-based filtering approach to measure the similarity between movies and recommend those that are closest to the user's past preferences.

- **Weighted Hybrid Recommendation**: Combines multiple recommendation strategies to provide more robust and accurate suggestions by balancing content-based filtering and collaborative filtering.

- **Collaborative Filtering**: Analyzes user behavior and preferences to suggest movies based on the ratings and choices of similar users.

- **Data Cleaning**: Ensures the dataset is clean and well-structured by handling missing values, removing duplicates, and normalizing data to improve the accuracy of the recommendation algorithms.

## Machine Learning Algorithms Used
- **Content-Based Filtering**: Utilizes metadata of movies to recommend similar ones.
- **Cosine Similarity**: Calculates similarity between movies based on their features.
- **Collaborative Filtering**: Uses user behavior and preferences for recommendations.
- **Hybrid Recommendation System**: Combines content-based filtering and collaborative filtering with a weighted approach for better accuracy.

## Getting Started

### Prerequisites
- Python 3.x
- Libraries: Pandas, NumPy, Scikit-learn, and other required dependencies.

### Installation
Clone the repository and install the required libraries using `pip`.

```bash
git clone <repository-url>
cd movie-recommendation-system
pip install -r requirements.txt
