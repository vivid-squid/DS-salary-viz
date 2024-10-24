# DATA SCIENCE CAREER ATLAS

This project provides an analysis of global AI, ML, and Data Science salaries using data sourced from [Kaggle](https://www.kaggle.com/datasets/dparas01/global-ai-ml-data-science-salary). The dataset has been processed and visualized to understand trends across different job roles, experience levels, and company sizes, including comparisons based on remote work settings.

## Data Source

The dataset used in this project was sourced from Kaggle: [Global AI, ML, Data Science Salary](https://www.kaggle.com/datasets/dparas01/global-ai-ml-data-science-salary).

## Transformations Applied

The following transformations were performed on the dataset:

1. **Data Cleaning & Deduplication**:
    - Removed duplicates to ensure each data entry was unique.
    - Cleaned the data to fix inconsistencies and handle missing values.

2. **Remote Work Categorization**:
    - Transformed or categorized `remote_ratio` into descriptive terms:
        - `No Remote Work`: Fully on-site roles.
        - Other categories for partial or fully remote roles.

3. **Data Visualization**:
    - The processed data was used to create a detailed dashboard using Tableau. 
    - The workbook file `DS_jobs_visualization.twb` contains the dashboard setup.
    - A report accompanies the project to explain the design choices, logic, and reasoning behind the creation of the dashboard.
    - A screenshot of the dashboard is provided for reference, and a video demonstration is available that shows the complete working of the dashboard.

## Dashboard Overview

The project includes a Tableau dashboard that visualizes key insights from the processed data. Key features of the dashboard:
- **Salary Trends**: Comparison of salaries across job roles, locations, and company sizes.
- **Remote Work Analysis**: Distribution of job roles by remote work categories.
- **Experience Level Comparison**: Analysis of how experience levels impact salary ranges.

## Files Included

- `fully_modified_salaries.csv`: The processed dataset used for the analysis.
- `DS_jobs_visualization.twb`: Tableau workbook file containing the dashboard setup.
- `dashboard_report.pdf`: Report detailing the creation and logic behind the dashboard.
- `screenshot.png`: Screenshot of the final dashboard.
- `dashboard_demo.mp4`: Video demonstration showing the complete working of the dashboard.

## Installation & Usage

1. **Install Dependencies**:
    - Ensure you have Python installed.
    - The following Python libraries are required:
      ```
      pip install pandas matplotlib numpy tqdm
      ```
2. **Run the Code**:
    - Use the `fully_modified_salaries.csv` file to load and analyze data.
    - Open the `DS_jobs_visualization.twb` file in Tableau to explore the dashboard.