# NoSQL Data Analysis Project

This project is designed to help you get started with NoSQL databases and perform data analysis using Python and MongoDB. It includes two Jupyter notebooks: one for setup and one for performing analysis.

## Project Structure

- `NoSQL_setup_starter.ipynb`
   Sets up the MongoDB database, imports data (establishments.json), and prepares collections for analysis.
- `NoSQL_analysis_starter.ipynb`
   Performs data queries, aggregations, and analysis using PyMongo and pandas. This notebook demonstrates how to extract insights from the NoSQL dataset.

### NoSQL_Setup

- Connects to your MongoDB database
- Loads a JSON dataset
- Inserts that dataset into a MongoDB collection
- Verifies that the data is in place
  - This notebook **must be run before** the analysis notebook, since it populates the data you'll analyze

### NoSQL_Analysis

- Connecting to MongoDB
- Retrieving and filtering documents
- Aggregating and summarizing data
- Preparing results for data science workflows

## Summary

The notebook connects to your MongoDB collection, queries the data to answer meaningful questions, summarizes it using groupings and counts, and prepares the results for further analysis using pandas.