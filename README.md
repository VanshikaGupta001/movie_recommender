<h1>Movie Recommendation System</h1>

Name: Vanshika Gupta
Roll number: cse240001076

This project is a Movie Recommendation System built using collaborative filtering with Singular Value Decomposition (SVD). It leverages the MovieLens dataset to train a model that predicts user ratings for unseen movies. The system integrates Pinecone, a vector database, to store and retrieve movie embeddings efficiently for real-time recommendations.

<b>Features</b>

Loads the MovieLens recent ratings dataset from Hugging Face.

Uses Surprise library for collaborative filtering via SVD.

Stores predicted movie ratings as embeddings in Pinecone.

Retrieves movie recommendations based on similarity.

Displays movie posters alongside recommendations.

<b>Installation</b>

Make sure you have Python 3.7+ installed. Then, install the required dependencies:

pip install -qU pinecone-client==3.1.0 datasets surprise pandas numpy

<b>Usage</b>

Clone the repository:

git clone https://github.com/VanshikaGupta001/movie_recommender

Run the script:

python movie_recommender.py

Enter a movie name when prompted to get recommendations.

<b>How It Works</b>

Loads the MovieLens dataset and processes it into a Pandas DataFrame.

Trains an SVD model using user ratings.

Stores the predicted ratings as embeddings in Pinecone.

Retrieves similar movies based on predictions.

Displays the original movie and recommended ones with posters.

<b>Dependencies</b>

pinecone-client

datasets

surprise

pandas

numpy

IPython
