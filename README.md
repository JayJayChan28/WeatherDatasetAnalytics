
# WeatherDatasetAnalytics
=======
# WeatherDatasetAnalytics# WeatherDatasetAnalytics
>>>>>>> add_image

## Project Overview
This project conducts an Exploratory Data Analysis (EDA) on global land temperature datasets to explore long-term climate trends. The goal is to visualize and statistically analyze temperature patterns over time, focusing on the impacts of climate change.

## Datasets
The analysis uses historical temperature data from the Berkeley Earth dataset, available on Kaggle. Four datasets were utilized:
- Global Land Temperatures by City
- Global Land Temperatures by Country
- Global Land Temperatures by State
- Global Average Temperatures

## Key Steps and Methodology

1. **Data Cleaning & Preparation**
   - Removed missing values primarily concentrated in pre-1850 records to focus on more reliable modern data.
   - Converted date columns to proper `Date` types for time series analysis.
   - Created additional columns for `year` and `decade` to enable time-based grouping.

2. **Summary Statistics**
   - Calculated global average temperatures per decade.
   - Identified the top 5 hottest and coldest years.
   - Computed temperature variance per decade.

3. **Visualizations**
   - Line charts showing global average temperature trends over time.
   - Boxplots to display temperature distributions by decade.
   - Country-specific temperature trends (e.g., United States).

4. **Hypothesis Testing**
   - Conducted a permutation test to assess whether the post-1950 increase in US average temperature is statistically significant.
   - The test yielded a p-value of approximately 0.0275, allowing us to reject the null hypothesis at the 5% significance level.

## Key Findings
- There is a clear upward trend in global average temperatures, especially since the mid-20th century.
- The variance in temperature appears to have slightly decreased over the decades.
- Statistical testing confirms that the temperature increase in the US after 1950 is unlikely due to random variation.

## Tools and Technologies
- **R Programming Language**
- **Tidyverse** for data manipulation and visualization
- **Infer** package for statistical inference
- **ggplot2** for data visualization

## How to Run
1. Clone this repository: git clone https://github.com/JayJayChan28/WeatherDatasetAnalytics.git
2. Open the `.qmd` file in RStudio or any Quarto-supported IDE.
3. Install required R packages:
```r
install.packages(c("tidyverse", "infer", "ggplot2"))
<<<<<<< HEAD

=======
>>>>>>> add_image
