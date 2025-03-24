Steps Performed:

step1:Data Loading: 
                Loads data from JSON (electricity) and CSV (weather) files into separate DataFrames.

step2:Data Cleaning: 
                Handles missing values (e.g., forward-filling temperature values), ensures the datetime columns are standardized, and checks for duplicates.

Step3:Merging Data:
                 Merges the two datasets based on the datetime column and removes duplicates.

step4:Final Output: 
                Saves the final cleaned and merged data into a CSV file.

step5: Libries used :

=> os: Used for file and folder path management and listing files in directories.

=> pandas: Used for data manipulation, including reading, merging, cleaning, and saving data.

=> json: Used to parse and extract data from JSON files



Final output is:

This code merges and cleans electricity and weather data, handling missing values, duplicates, and saving the merged dataset.