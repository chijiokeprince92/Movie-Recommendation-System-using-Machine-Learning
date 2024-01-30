# Movie Recommendation System

This repository contains a movie recommendation system that combines both symbolic and non-symbolic artificial intelligence methods. The system utilizes the IMDb Movies Dataset and provides personalized movie recommendations based on a combination of symbolic features such as overview, keywords, writer, director, and cast.

## Overview

The movie recommendation system aims to enhance user experience by employing a hybrid approach, incorporating both symbolic and non-symbolic AI techniques. By leveraging information about the movie's overview, keywords, writer, director, and cast, the system provides more accurate and personalized recommendations.

## Features

1. **Symbolic Features:**
   - **Overview:** Utilizes the movie's overview to understand its plot and theme.
   - **Keywords:** Extracts keywords associated with each movie to capture its essence.
   - **Writer, Director, and Cast:** Considers the involvement of specific writers, directors, and cast members in the recommendation process.

2. **Non-Symbolic Features:**
   - Employs collaborative filtering and content-based filtering techniques to analyze user preferences and similarities between movies.
   - Utilizes machine learning algorithms to learn patterns and make personalized recommendations.

3. **Dataset:**
   - The IMDb Movies Dataset is used as the primary data source, providing a comprehensive collection of movies with various attributes.

4. **Recommendation Engine:**
   - Implements a recommendation engine that combines both symbolic and non-symbolic features to generate accurate and diverse movie suggestions.

## Setup Instructions

### 1. Prerequisites

- Python 3.x installed
- Necessary Python packages installed (install with `pip install -r requirements.txt`)

### 2. Dataset

- Download the IMDb Movies Dataset and place it in the `dataset` directory.


### 4. Running the Recommendation System

- Execute the main recommendation notebook: `movies_recommendation_system.ipynb`
- The system will process the dataset, analyze user preferences, and generate personalized movie recommendations.

## Evaluation and Testing

- The system's performance can be evaluated using metrics such as precision, recall, and F1 score.
- Conduct testing with sample users to validate the accuracy and effectiveness of the recommendations.

## Contributing

Feel free to contribute to the development of this recommendation system by submitting issues, feature requests, or pull requests.

## License

This movie recommendation system is licensed under the [MIT License](LICENSE).
