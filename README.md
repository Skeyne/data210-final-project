# data210-final-project

Documentation on /Scripts, and what everything in there is for:

s3.py : Complies commonly used functions to be callable in other scripts.

applicant_details_transformation.py : Creates dataframe from all applicant csv, cleans data and creates unique ID.

academy_cleaned.ipynb : Creates dataframe from all academy csv, cleans data. (Note:will be changed to .py in future)

json_pandas.py : Converts data provided by client in JSON format to a pandas dataframe, then creates seperate dataframes for strenghts and weaknesses.

sparta_day_transformation.py: Defines a function to parse text files provided by client, reads text files and writes them to a pandas dataframe, cleans the data and creates a unqiue ID. 

create_database.py : Creates initial database and tables using SQLAlchemy.
