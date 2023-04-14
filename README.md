# data210-final-project

### Requirements:
  - Docker container 
  - Microsoft SQL server hosted locally
  - Python modules as per requirements.txt

# Documentation on /Scripts:

### main.py
Point of entry for the pipeline, this creates the tables, extracts and transforms the data in S3 and inserts into the databasee

#### s3.py
Complies commonly used functions to be callable in other scripts.

#### applicant_details_transformation.py
Creates dataframe from all applicant csv, cleans data and creates unique ID.

#### academy_cleaned.ipynb
Creates dataframe from all academy csv, cleans data. (Note:will be changed to .py in future)

#### json_pandas.py
Converts data provided by client in JSON format to a pandas dataframe, then creates seperate dataframes for strenghts and weaknesses.

#### sparta_day_transformation.py
Defines a function to parse text files provided by client, reads text files and writes them to a pandas dataframe, cleans the data and creates a unqiue ID. 

#### create_database.py
Creates initial database and tables using SQLAlchemy.

#### academy_behaviours.py
Creates behaviour, spartans, course and trainer dataframes from academy data.

#### self_tech_scores.py
Obtains the tech scores from JSON files as a csv.

#### talent_sparta_results.py
Outputs key interview metrics as a csv.
