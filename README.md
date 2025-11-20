# 🎬 Movie Recommender System (SVD-Based)

This project is a simple end-to-end movie recommendation system built using the MovieLens 25M dataset.  
It demonstrates how to:

- Load and explore a large-scale movie ratings dataset  
- Build a sparse user–item matrix  
- Apply Truncated SVD to learn latent user/movie features  
- Predict ratings and recommend movies  
- Find similar movies using cosine similarity  

The project is implemented entirely inside a Jupyter Notebook:  
`movie_recommender.ipynb`


This project uses the **MovieLens 25M dataset**, available at:

https://grouplens.org/datasets/movielens/25m/  
Dataset provided by **GroupLens Research, University of Minnesota**.

It is automatically downloaded by the notebook during execution.

Currently, it is a console based tool that:
1. Recommends movies for a given user
2. Find similar movies

Might develop into web interface model as I progress 


# How to Run & Test

## Option 1 — Run on Google Colab (Easiest)

1. Upload the notebook to Google Drive  
2. Open it in Colab  
3. Make sure runtime has Python 3 + GPU (optional)  
4. Run all cells  

The notebook automatically downloads the dataset from GroupLens.

You do *not* need to install anything manually.


## Option 2 — Run Locally

Clone the Repository

and just run the movie_recommender.ipynb file in an IDE.


