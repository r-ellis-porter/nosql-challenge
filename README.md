# UK Food Standards Agency Data Analysis

## Overview

Welcome to the UK Food Standards Agency Data Analysis repository! This project aims to evaluate food hygiene ratings provided by the UK Food Standards Agency, assisting food magazine editors and critics in identifying establishments for future articles and reviews.

The project involves three main parts:

1. **Database Setup**: Importing data from establishments.json into a MongoDB database named uk_food and preparing it for analysis using PyMongo.
2. **Database Update**: Updating the database according to the magazine editors' requests, including adding a new restaurant, updating business types, and removing establishments from specific areas.
3. **Exploratory Analysis**: Conducting exploratory analysis to answer specific questions posed by the magazine editors, such as identifying establishments with certain hygiene scores, high ratings, and proximity to a new restaurant.

## Important Findings

### Exploratory Analysis

1. **Establishments with Hygiene Score of 20**: There are 41 establishments with a hygiene score of 20. For example, "The Chase Rest Home" in Eastbourne has a hygiene score of 20.
2. **High-Rated Establishments in London**: 33 establishments in London have a rating value greater than or equal to 4, including pubs, restaurants, and other catering premises.
3. **Top 5 Establishments with Rating Value of 5**: The top 5 establishments with a rating value of 5, sorted by lowest hygiene score and nearest to "Penang Flavours" in Greenwich, include pubs, nurseries, and takeaway shops.
4. **Local Authority Areas with Hygiene Score of 0**: The number of establishments with a hygiene score of 0 varies across different local authority areas. For example, Plumstead in Greenwich has several establishments with a hygiene score of 0.

## Technical Details

### Part 1: Database and Jupyter Notebook Setup

- Use `NoSQL_setup_starter.ipynb` for database setup and data import.
- Import the data from `establishments.json` into the `uk_food` database and `establishments` collection.
- Libraries used: PyMongo and Pretty Print (pprint).

### Part 2: Update the Database

- Make modifications to the database as requested by the magazine editors, such as adding new establishments, updating business types, and converting data types.
- Use `NoSQL_setup_starter.ipynb` for this section.

### Part 3: Exploratory Analysis

- Use `NoSQL_analysis_starter.ipynb` for conducting exploratory analysis.
- Explore specific questions using MongoDB queries and aggregation methods.
- Display results using pprint and convert them into Pandas DataFrames for further analysis.

## Screenshots

Screenshots of data analysis results, including query outputs and DataFrame previews, will be included in the notebook for reference.

## Running the Code

To run the code, ensure you have MongoDB installed and running. Import the provided data into your MongoDB database. Then, execute the code cells in the Jupyter notebooks provided for each part of the project.
