# ApprovalMax_test
Technical task from ApprovalMax

## Task Description

You have a dataset. 
Please, do the following:
  - Get a dataframe pd.util.testing.makeDataFrame() - df
  - Make a column ‘date’ depending on the index value. 
    - Day equals the last letter index (no matter which register the letter is). A/a == 1, B/b == 2 etc. 
    - Month equals the number of the row (sorted by the index ascending) in cycling mode 1 to 12.
    - If the number of vowels is greater than the number of consonants then the year should be 2021, otherwise - 2022.
  - Make a pivot table showing dynamics of every column by months (agg is sum). + Charts for every column - save into df_months1
  - Make a full date list between min dataframe date and max dataframe date to include dates without values and make a pivot table with dates as columns and current columns as index (agg is sum). Save into df_days. Drop all columns with even-numbered days. - save into df_days1
  - df_days - delete row with minimal sum of all elements and take only every third column as a result. Save into df_days2.
  - Write an ETL class structure. Imagine the situation that you have an abstract API (let’s say https://blahblahblah.com/api/v1/?reportId=123) to download the data from and a DWH to upload data to. Please prepare a structure of python classes how you’d do the ETL. Logic of every method may be described with comment (without a code). But you should mention libs that’d be used.
