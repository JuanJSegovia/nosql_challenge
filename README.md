# NoSQL Challenge: UK Food Standards Database

##Overview

The project focuses on using MongoDB to manage, query, and update the database, as well as conducting exploratory analysis to provide insights into the food hygiene ratings of various establishments.

## Project Breakdown

### Part 1: Database and Setup
Import the dataset into a MongoDB collection called establishments.
Set up a connection to the MongoDB database in Jupyter Notebook.
Verify that the data has been properly imported by checking the databases and collections.

### Part 2: Database Updates
Add a new establishment to the database.
Update the business type for the newly added establishment.
Remove all establishments located in Dover from the database.
Convert some fields (e.g., latitude, longitude, RatingValue) to the appropriate data types.

### Part 3: Data Analysis
We perform several queries to answer specific questions posed by the magazine editors, including:

Finding establishments with specific hygiene scores.
Locating top-rated establishments close to a new restaurant.
Counting how many establishments in each Local Authority area have a hygiene score of 0.
### Files
NoSQL_setup_starter.ipynb: Jupyter Notebook for setting up the database and making necessary updates.
NoSQL_analysis_starter.ipynb: Jupyter Notebook for performing exploratory data analysis.
Resources/establishments.json: Dataset containing information about various food establishments in the UK.

### How to Run the Project
Clone the repository.
Import the dataset into MongoDB.
Open the provided Jupyter notebooks to perform the database setup and analysis.
