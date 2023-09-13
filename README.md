# NoSQL Challenge
## Module 12 Challenge

### Overview
The following repository uses MongoDB via PyMongo to import a [JSON file](Resources/establishments.json) containing data regarding food-serving establishments in the United Kingdom. In the [setup document](NoSQL_setup.ipynb), I import the JSON file and create a database on MongoDB, update the database to include a new entry, and edit that entry. I then alter the data types of quantitative data, converting latitude, longitude, and ratings data to the appropriate numerical types in order to allow for easier querying later. In the [analysis document](NoSQL_analysis.ipynb), I answer various questions about trends in the data by applying basic query tools and aggregation pipelines. For each answer set, I construct a pandas DataFrame to display the results. 

### Outside Sources
The following code was developed solely by me, with no assistance from other students, instructors, tutors, or TAs. I did use StackOverflow to discover the $project aggregate of MongoDB, then read the MongoDB documentation to understand how to apply the function so that I could examine multiple types at once to check my type changes at the end of the setup document. 
