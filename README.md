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
- Company productivity has had a mild downward trend over time
- Team size has a weak relationship with performance deviation
- Incentives have a mild but inconsistent effect
- Idle time is strongly associated with lower productivity
- Overtime shows diminishing returns on productivity
- Overall system performance is more influenced by efficiency than scale

## How to Run
Open `analysis.ipynb` in Jupyter Notebook or VS Code and run all cells sequentially.

OR in a terminal:
```
git clone https://github.com/CollinVanderbilt5/employee-productivity-analysis.git
pip install -r requirements.txt
jupyter notebook
