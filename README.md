# Movies-ETL
BookCamp Week 8 
# Overview
From the previous code made in this module,  we need to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. We will refactor  to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

# Sumary 
In this  module we learned the ETL process: Extract, Transform, Load process for collect, cleaning, and saving data sets previous data analyis. It is a very important and exhaustive process,  because from the purity of the origin data, our analysis will be more reliable.  
To perform this job, we used list comprehension, lambda functions and regular expressions as part of the job: We need to inspect first the data looking for something weird or incomplete, take decisions about the steps we need to perform and be patient!! The final work will depend of the cleanliness of our work.
Finally, we converted via sqlachemy to SQL database, in order to visualize and manipulate the data in PostgreSQL.





