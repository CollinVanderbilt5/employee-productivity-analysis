# Employee Productivity Analysis

## Overview
This project analyzes employee productivity data to understand how factors such as overtime, incentives, idle time, and team size influence performance relative to expected output.

The goal is to identify key drivers of productivity deviation and provide data-driven insights into workforce efficiency.

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib
- Jupyter Notebook

## Dataset
The dataset contains employee-level productivity metrics including:
- Actual productivity
- Targeted productivity
- Overtime
- Idle time
- Incentives
- Team sizes

## Key Insights
- Team size had no substantial relationship with performance deviation
- Overtime also has no noticeable correlation with productivity
- Incentives have a moderate but inconsistent effect, meaning it could be useful but not on its own
- Idle time is strongly associated with lower productivity
- Thus, overall system performance is likely more influenced by workflow inefficiency than scale

To see more in-depth insights and data, go to the bottom of employee_productivity_analysis.ipynb

## How to Run
Open `employee_productivity_analysis.ipynb` in Jupyter Notebook or VS Code and run all cells sequentially.

OR in a terminal:
```
git clone https://github.com/CollinVanderbilt5/employee-productivity-analysis.git
pip install -r requirements.txt
jupyter notebook
