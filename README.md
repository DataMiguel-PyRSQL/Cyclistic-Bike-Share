# Cyclistic-Bike-Share
---

### Data Availability Notice

Due to GitHub's file size limitations, it was not possible to upload the full dataset used in this project. The original dataset comprises **12 months of data**, totaling more than **1.2 GB**, with over **6 million rows** and **13 columns**. 

As a result, only **5 months of data** are included in this repository, representing a subset of the original dataset. However, the complete dataset, along with detailed specifications of all 12 months used in this project, is referenced and processed within the R Markdown file (`Case_Study1.Rmd`). 

A link to the original dataset and instructions on how to reproduce the analysis with the full dataset are provided in the R Markdown file.

## Project Overview
This project is part of a Capstone assignment from Google’s Data Analytics Professional Certificate. The objective is to analyze user behavior data from Cyclistic, a bike-sharing company in Chicago, to identify differences between casual riders and annual members. The insights derived will help inform a marketing strategy aimed at converting casual riders into annual members.

## Methodology
1. **Data Cleaning:** Removed duplicates, handled missing values, and formatted date-time columns.
2. **Data Analysis:** Grouped and summarized data to identify trends and patterns in usage.
3. **Visualization:** Created charts and graphs to illustrate key differences between member and casual riders.
4. **Recommendations:** Developed actionable insights based on the analysis to help Cyclistic improve conversion rates and user satisfaction.

## Files Included
- `Case_Study1.Rmd` - The R Markdown file containing the full analysis, including data cleaning, exploration, and visualization.
- `data/` - A folder containing the raw data files (`.csv`) for 12 months.

## Tools and Packages
The project was developed using R and the following libraries:
- `tidyverse`
- `ggplot2`
- `geosphere`
- `lubridate`

## How to Run the Project

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/DataMiguel-PyRSQL/Cyclistic-Bike-Share.git
2. Place the raw data files in the `data` folder.
3. Open the R Markdown file (`Case_Study1.Rmd`) in RStudio.
4. Install the required libraries if you haven’t already:
   ```bash
    install.packages(c("tidyverse", "ggplot2","geosphere","lubridate"))
5. Knit the R Markdown file to generate the report in HTML or PDF format.

## Key Findings

- Casual riders and annual members display distinct usage patterns, such as frequency and trip duration.
- Insights from these patterns can guide marketing strategies to target casual riders effectively.

## License

This project uses publicly available data from Divvy Bikes. By using this data, you agree to the terms specified in the [Divvy Data License Agreement](https://divvybikes.com/data-license-agreement).

## Author

[Miguel Aldana](https://www.linkedin.com/in/miguel-aldana-062568345/)

## Acknowledgments

Thanks to [Divvy Bikes](https://divvybikes.com/) for providing the data and to [Google Instructors](https://www.coursera.org/google-career-certificates) who supported the project.
   
