# HitPredict

## Project Overview

HitPredict is a machine learning project aimed at predicting the popularity of songs using Spotify data and building a personalized music recommendation system. This project leverages pandas for data manipulation, scikit-learn for machine learning, and various other libraries for analyzing and modeling song features.

## Features

- Predict song popularity based on various musical features.
- Build personalized music recommendations using collaborative and content-based filtering.
- Clean and analyze large datasets using pandas and NumPy.
- Train machine learning models using scikit-learn and TensorFlow.

## Setup & Installation

### Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- tensorflow (optional)
- matplotlib (optional, for visualization)

### Installation

Start by downloading the data at this link [30000 Spotify Songs](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs?resource=download&select=spotify_songs.csv)
and add in a folder `data` at the root of the project like this:

```
data/
    - spotify_songs.csv
notebooks/
.gitignore
README.md
```

Run this command to create a conda environment:

```
conda create -n hit_predict python=3.9 numpy pandas scikit-learn matplotlib seaborn jupyterlab
```

Activate your conda environment:

```
 conda activate hit_predict
```

Then select this environment to run
