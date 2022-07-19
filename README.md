# Nashville Housing Data Cleaning 

In this project, I am utilizing the power of data cleaning. Most raw data, whether text or images– often even data stored in spreadsheets – is improperly formatted, incomplete, or dirty and needs to be properly cleaned and structured before you begin your analysis. Usually when working with raw data I come across common problems such as: NULL data, duplicates, mismtched datatypes, inconsistent date formats, and mispelled words. The steps I took to prepare for the Nashville Housing data for potential processing and analyzing are:
1. Remove irrelevant data
2. Deduplicate your data (used join to fill out any empty data)
3. Deal with missing data
4. Create new columns to separate the Addresse, City, and State (using parsename and altering the entire table)
