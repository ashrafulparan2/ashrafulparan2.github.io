---
title: 'Movie Recommender'
excerpt: 'A personalized movie recommendation system using collaborative and content-based filtering'
author_profile: true
permalink: /projects/movie-recommender/
---

<head>
<title>Font Awesome Icons</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>

# Movie Recommender

[<i class="fa fa-github" style="color:black;"></i> View on GitHub](https://github.com/ashrafulparan2/Movie-Recommender)

## Overview
The Movie Recommender is a web application that provides personalized movie recommendations using advanced recommendation algorithms. Built with Streamlit, it offers an intuitive interface for users to discover new movies based on their preferences and viewing history.

## Key Features
- Personalized movie recommendations using collaborative filtering
- Content-based filtering based on movie characteristics
- Interactive user interface with dynamic recommendation updates
- User input forms for preference customization
- Real-time recommendation generation

## Technical Details
- **Framework**: Streamlit
- **Algorithms**: Collaborative Filtering, Content-based Filtering
- **Technologies**: Python, Pandas, Scikit-learn
- **Duration**: Oct 2023 – Dec 2023

## Project Highlights
- Successfully implemented multiple recommendation algorithms
- Created an engaging and user-friendly interface
- Integrated real-time recommendation updates
- Optimized for performance and user experience

## Project Documentation
Below is the README content from the GitHub repository:

# Project: Movie Recommender System Using Machine Learning!

<img src="/assets/images/projects/movie-recommender/6.jpeg" alt="workflow" width="70%">

Recommendation systems are becoming increasingly important in today's extremely busy world. People are always short on time with the myriad tasks they need to accomplish in the limited 24 hours. Therefore, the recommendation systems are important as they help them make the right choices, without having to expend their cognitive resources.

The purpose of a recommendation system basically is to search for content that would be interesting to an individual. Moreover, it involves a number of factors to create personalised lists of useful and interesting content specific to each user/individual. Recommendation systems are Artificial Intelligence based algorithms that skim through all possible options and create a customized list of items that are interesting and relevant to an individual. These results are based on their profile, search/browsing history, what other people with similar traits/demographics are watching, and how likely are you to watch those movies. This is achieved through predictive modeling and heuristics with the data available.

# Types of Recommendation System :

### 1 ) Content Based :

- Content-based systems, which use characteristic information and takes item attriubutes into consideration .
- Twitter , Youtube .
- Which music you are listening , what singer are you watching . Form embeddings for the features .
- User specific actions or similar items reccomendation .
- It will create a vector of it .
- These systems make recommendations using a user's item and profile features. They hypothesize that if a user was interested in an item in the past, they will once again be interested in it in the future
- One issue that arises is making obvious recommendations because of excessive specialization (user A is only interested in categories B, C, and D, and the system is not able to recommend items outside those categories, even though they could be interesting to them).

### 2 ) Collaborative Based :
		
- Collaborative filtering systems, which are based on user-item interactions.
- Clusters of users with same ratings , similar users .
- Book recommendation , so use cluster mechanism .
- We take only one parameter , ratings or comments .
- In short, collaborative filtering systems are based on the assumption that if a user likes item A and another user likes the same item A as well as another item, item B, the first user could also be interested in the second item . 
- Issues are :
  - User-Item nXn matrix , so computationally expensive .
  - Only famous items will get reccomended .
  - New items might not get reccomended at all .   

### 3 ) Hybrid Based :
	
- Hybrid systems, which combine both types of information with the aim of avoiding problems that are generated when working with just one kind.
- Combination of both and used now a days .
- Uses : word2vec , embedding .           

# About this project:

This is a streamlit web application that can recommend various kinds of similar movies based on an user interest.
here is a demo,

* [Click here to run it live on server](https://movie-recommeder-system.herokuapp.com/)

# Demo:

<img src="/assets/images/projects/movie-recommender/1.png" alt="workflow" width="70%">

<img src="/assets/images/projects/movie-recommender/2.png" alt="workflow" width="70%">

<img src="/assets/images/projects/movie-recommender/3.png" alt="workflow" width="70%">

# Dataset has been used:

* [Dataset link](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

# Concept used to build the model.pkl file : cosine_similarity

1 . Cosine Similarity is a metric that allows you to measure the similarity of the documents.

2 . In order to demonstrate cosine similarity function we need vectors. Here vectors are numpy array.

3 . Finally, Once we have vectors, We can call cosine_similarity() by passing both vectors. It will calculate the cosine similarity between these two.

4 . It will be a value between [0,1]. If it is 0 then both vectors are complete different. But in the place of that if it is 1, It will be completely similar.

5 . For more details , check URL : https://www.learndatasci.com/glossary/cosine-similarity/

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/entbappy/Movie-Recommender-System-Using-Machine-Learning.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n movie python=3.7.10 -y
```

```bash
conda activate movie
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
#run this file to generate the models

Movie Recommender System Data Analysis.ipynb
```

Now run,
```bash
streamlit run app.py
``` 