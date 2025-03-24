
=>   This code reads data from the merged dataset located at:(merged_dataset.csv)

Here’s a simple list of what the code does:

Step1: Missing Data:
            Fills missing categorical data with "Unknown".
            Fills missing numerical data with the median of the column.

Step2:Data Type Conversions:
            Converts categorical columns to category type.
            Converts datetime strings to datetime objects.

Step3:Duplicates:
            Removes duplicate rows.

step4:Outliers:
            Removes outliers from the "value" column using Z-scores.

Step5:Feature Engineering:
            Creates new columns: Hour, Day, Month, Day of the Week, and Weekend Flag based on the datetime column.

Step6:Documentation:
            Inline comments explain the steps, such as handling missing data, removing duplicates, and creating new features.

Step7:Libraries Used:
         os: File path handling and checking.
        pandas: Data manipulation (loading, cleaning, saving).
        numpy: Handling numerical operations and outlier removal.



Final output is:

            This code cleans and processes the merged dataset by handling missing values, removing outliers, and adding new features, then saves the cleaned data to a CSV file.




