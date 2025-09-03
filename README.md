# Dataset_Preprocessing

## Steps

1. Obtained Netflix Film & TV Shows dataset from Kaggle
2. Used Pandas library with Python to perform preliminary cleaning and preprocessing of dataset
   - Removed records with missing values (None, NaN, Null or empty)
   - Dropped the column 'index' as 'show_id' can reliably serve as alternative
   - Removed duplicate records, only retaining the first instance in each case
   - Stripped additional whitespaces in the 'date_added' column
   - Changed datatype of column 'date_added' from object to datetime[64]
3. Stored cleaned dataset as a new csv file

## Things to improve, Answers to seek

1. What are best practices for dropping records from a dataframe? Is dropping every record with even a single missing value a viable option?
2. Should I have stripped whitespaces from the other object type columns, or is retaining the data in its original state a better option?
3. What are some other preprocessing steps that can be used to ensure the dataset is ready for analytics, visualization and model training?
