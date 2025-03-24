=> This code read data from  newmerged.csv 

Here are the concise steps:

Step1:Detect Outliers: 
            Use IQR and Z-score methods to identify outliers.

Step2:Handle Outliers:
             Remove outliers based on detection results.

Step4:Visualize: 
            Plot before and after distributions.


Libraries used Here:

    => os: File path manipulation and checking if files exist.

    => pandas: Data manipulation (loading data, handling dataframes).

    => numpy: Numerical operations (for Z-score calculation).

    => matplotlib: Data visualization (plotting before and after).

    =>seaborn: Enhanced visualization (boxplots, histograms).

    =>scipy: Statistical methods (Z-score calculation for outlier detection).



Fianal Output is :
                Save Cleaned Data: Save cleaned dataset as final_file.csv.