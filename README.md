# Spotify Recommendation System

## Overview
This document outlines the structure and functionality of a recommendation system for Spotify built using Python. This project allows users to create personalized music recommendations based on their preferences, leveraging Spotify's API and machine learning techniques.

## Directory Structure

```bash
Spotify_Recommendation_System/
├── LICENSE
├── README.md
├── Recommandation_System.ipynb
├── datasets
│   ├── data.csv
│   ├── data_by_genres.csv
│   └── data_by_year.csv
├── requirements.yml
└── static
    ├── Screen
    │   ├── Screen_2.png
    │   ├── Screen_3.png
    │   ├── Screen_4.png
    │   └── Screen_5.png
    ├── emoji.png
    ├── logo.png
    └── warning.png

4 directories, 14 files
```


## Key Components
- `Recommandation_System.ipynb`: The main Jupyter Notebook containing the implementation of the recommendation system, including data preprocessing, model training, and evaluation.
- `datasets/`: Contains datasets used for training and testing the recommendation system.
  - `data.csv`: The processed dataset with audio features.
  - `data_by_genres.csv`: Dataset containing aggregated data grouped by music genres.
  - `data_by_year.csv`: Dataset containing aggregated data grouped by release year.
- `static/`: Contains static assets such as images.
  - `Screen/`: Screenshots related to the application setup and usage.
    - `Screen_2.png`, `Screen_3.png`, `Screen_4.png`, `Screen_5.png`: Step-by-step screenshots for setting up the Spotify app.
  - `emoji.png`, `logo.png`, `warning.png`: Additional images used in the documentation or interface.


## Getting Started

To get started with this tutorial, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone git@github.com:nameisalfio Spotify_recommendation_system.git
   cd Spotify_recommendation_system
    ```

2. **Set Up the Virtual Environment Create and activate the Conda environment**:
   ```bash
   conda env create -f environment.yml
   conda activate smda
   ```

3. **Install Dependencies Ensure all required Python packages are installed**:

    ```bash
    pip install -r requirements.txt
    ```

4. Create a .env file with your Spotify credentials:

    ```bash
    SPOTIPY_CLIENT_ID=your_client_id
    SPOTIPY_CLIENT_SECRET=your_client_secret
    SPOTIPY_REDIRECT_URI=http://localhost:5000/callback
    ```

5. **Explore the Jupyter Notebook Open the Jupyter notebook to follow the step-by-step implementation of the recommendation system**:

    ```bash
    jupyter notebook Recommandation_System.ipynb
    ```

## Key Features

- Personalized Recommendations : Generate song recommendations based on user preferences.
- Audio Feature Analysis : Explore trends in audio features such as valence, energy, and danceability.
- User Profiling : Create user profiles by analyzing liked songs and generating mean vectors.
- Dataset Creation : Extract and preprocess data from Spotify's API to build custom datasets.
- Evaluation Metrics : Assess the system's performance using Precision, Recall, and F1-score.

## Contributing
Contributions to this project are welcome! If you'd like to suggest improvements or report issues, please submit a pull request or open an issue through the appropriate channels.

## Conclusion
This Spotify Recommendation System offers a robust and customizable solution for generating personalized music recommendations. With its integration of Spotify's API and machine learning techniques, it serves as a solid foundation for building advanced recommendation systems. I encourage you to explore the capabilities of this application and contribute to its development.

## License
This project is licensed under the MIT License - see the LICENSE file for details.