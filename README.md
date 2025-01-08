# Eat Safe, Love

## Summary
This project involves the analysis and updating of a food establishments database using MongoDB and Python. The goal is to perform data operations such as adding new entries, updating existing ones, and executing exploratory data analysis to gain insights from the data.

## Objectives
- Import data from a JSON file into MongoDB.
- Perform various update operations on the database.
- Conduct exploratory data analysis to identify patterns and trends.
- Utilize Python libraries like PyMongo and Pandas for database operations and analysis.

## Data Description
The dataset includes:
- **Food Establishments Data**: Information about various food establishments including business name, type, address, and hygiene scores.

## Scripts Included
1. **Database and Jupyter Notebook Set Up**: 
   - Imports the data from a JSON file into MongoDB.
   - Sets up the MongoDB client and database.

2. **Database Update and Exploratory Analysis**: 
   - Updates the database with new entries and modifies existing records.
   - Performs exploratory data analysis to extract meaningful insights.

## Requirements
- Python 3.10
- pymongo module
- pandas module
- pprint module

## Instructions

### Database and Jupyter Notebook Set Up
1. Ensure the necessary libraries are installed.
2. Use the following command to import the dataset:
   ```markdown
   `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`
3. Run the `part_1_database_setup.ipynb` script.

### Database Update and Exploratory Analysis
1. Ensure the necessary libraries are installed.
2. Run the `part_2_database_update.ipynb` script.

## Contributions
Contributions are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.
