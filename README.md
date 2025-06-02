# Task1_elevatelabs
Here is a short README.md that explains what was done in my code and describes the dataset:
---
# Netflix Titles Data Cleaning
## Dataset Overview
The dataset (netflix_titles_modified.csv) contains information about movies and TV shows available on Netflix. Some key columns include:

* *title*: Name of the show/movie
* *type*: Whether it's a Movie or TV Show
* *director*: Director's name
* *cast*: Main actors
* *country*: Country of origin
* *date\_added*: Date the content was added to Netflix
* *release\_year*: Year the content was released
* *rating*: Age rating (e.g., PG, TV-MA)
* *duration*: Length of the content
* *listed\_in*: Categories or genres
* *description*: Brief summary of the content

---

## What the Code Does

This script performs basic data cleaning and preparation steps to make the dataset ready for analysis:

1. *Load the CSV file*
   Reads the dataset using pandas.read_csv().

2. *Inspect Missing Values*
   Prints the count of missing values in each column before cleaning.

3. *Remove Duplicates*
   Removes any duplicate rows to ensure data uniqueness using .drop_duplicates().

4. *Standardize Text*
   Strips extra spaces and converts country names to lowercase for consistency.

5. *Convert Dates*
   Converts the date_added column to proper datetime format.

6. *Clean Column Names*
   Renames all column headers to lowercase and replaces spaces with underscores for uniformity.

7. *Fix Data Types*
   Converts release_year to a numeric format with nullable integers (Int64).

8. *Inspect Cleaned Data*
   Prints data info and missing values after cleaning.

9. *(Optional)* Save the cleaned data to a new CSV file.

---
This cleaning step is essential to ensure the dataset is consistent, free from formatting issues, and ready for further analysis or visualization.
