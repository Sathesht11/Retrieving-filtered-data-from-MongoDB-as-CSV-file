# Retrieving-filtered-data-from-MongoDB-as-CSV-file
This method is used to retrieve only a filtered data from a MongoDB collection. First, mongoDB connection was made, in the collection.find() query, filtering query is added to read the data.The data is then transformed into a dataframe using the pandas library. Finally, the dataframe is saved as a csv file in the current working directory.

# Data
The sample data from MongoDB was used. The database is 'sample_mflix' and collection name is 'movies'.
