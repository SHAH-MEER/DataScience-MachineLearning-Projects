# Recommendation Systems Project

This directory contains implementations of three types of recommendation systems using Python and Jupyter notebooks:

- **Collaborative Filtering** (`Collabortive_Filtering_RS.ipynb`):
  - Uses the Surprise library for collaborative filtering (SVD).
  - Focuses on user-item interactions and predicts ratings based on similar users/items.

- **Content-Based Filtering** (`Content_Based_Filtering_RS.ipynb`):
  - Uses movie metadata and text features (e.g., genres, descriptions) with TF-IDF and cosine similarity.
  - Recommends items similar to those a user has liked, based on content features.

- **Popularity-Based Filtering** (`Popularity_Based_Filtering_RS.ipynb`):
  - Ranks items based on their popularity metrics (e.g., average rating, vote count).
  - Simple baseline method for recommendations.

## Data

The `data/` folder contains:
- `movies.csv`: Movie metadata.
- `credits.csv`: Cast and crew information.
- `ratings.csv`: User ratings for movies.

## How to Use

1. Open any notebook in Jupyter or a compatible environment.
2. Ensure required libraries are installed:
   - `pandas`, `numpy`, `scikit-learn`, `surprise` (for collaborative filtering)
3. Run the cells sequentially for each notebook to reproduce results and understand the workflow.

## Credits

This project is for educational purposes and demonstrates core approaches to building recommendation systems using real-world movie data.

---

Feel free to extend these notebooks with additional algorithms, visualizations, or datasets!
