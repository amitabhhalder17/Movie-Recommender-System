# Project Title
The goal of this project is to develop a movie recommendation system utilizing machine learning techniques. By analyzing user preferences, movie metadata, and historical data, this system aims to enhance the movie-watching experience by accurately predicting and recommending films that align with individual interests.

Key Phases of the Project
Data Collection and Preprocessing:A comprehensive dataset has been assembled, including attributes such as genre, director, cast, release year, and ratings. Additional data sources, such as user analytics and social media sentiment, may be incorporated to gain deeper insights into user preferences. The collected data undergoes preprocessing to address missing values, remove duplicates, and ensure relevance for subsequent analysis.

Recommendation Algorithms:
1. Collaborative Filtering: This technique analyzes users' rating patterns to recommend movies that similar users have enjoyed.
2. Content Filtering: This method recommends movies based on the characteristics of the films themselves, such as genre and director.
3. Hybrid Methods: These combine collaborative and content filtering approaches to leverage the strengths of both methods.

Model Training and Evaluation:The chosen machine learning models are trained on the preprocessed data to uncover patterns and relationships between films and users. The system is evaluated based on its ability to deliver accurate and personalized movie recommendations.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/amitabhhalder17/Movies-Reccomendation-System.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Movies-Recommendation-System
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Unzip the `similarity.zip` folder to extract the dataset:
    ```bash
    unzip similarity.zip
    ```
   This will extract a file named `similarity.pkl` to the project directory.

2. Run the main script:
    ```bash
    python main.py
    ```