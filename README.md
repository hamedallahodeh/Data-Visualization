# Mobile Device Usage and User Behavior Analysis

A data visualization project that explores mobile device usage patterns and user behavior using Python.

**Author:** Hamedallah Anwer Hamedallah Issa
**Student ID:** 320220603007

---

## Project Overview

This project analyzes a dataset of 700 mobile users to understand how people use their devices. It uses exploratory data analysis and visualizations to compare device popularity, screen time, data usage, and battery efficiency across different user groups.

## Dataset

- **Source:** [Mobile Device Usage and User Behavior Dataset (Kaggle)](https://www.kaggle.com/datasets/valakhorasani/mobile-device-usage-and-user-behavior-dataset)
- **Size:** 700 rows, 11 columns
- **Features:** User ID, Device Model, Operating System, App Usage Time (min/day), Screen On Time (hours/day), Battery Drain (mAh/day), Number of Apps Installed, Data Usage (MB/day), Age, Gender, User Behavior Class

## Visualizations

The notebook includes the following analyses:

1. **Device popularity:** most common device models among users
2. **Screen time by age and gender:** how daily screen-on time changes with age
3. **Average data usage by age group:** comparison across age groups (0-18, 19-25, 26-35, 36-50, 51-65)
4. **Battery efficiency by device:** battery drain per hour of screen time for each device model
5. **Top 5 users by app usage time:** the heaviest users in the dataset

## Tools and Libraries

- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

## Repository Contents

| File | Description |
|---|---|
| `Data_Vis_Project.ipynb` | Jupyter notebook with the full analysis and charts |
| `Data_Vis_project.pptx` | Presentation summarizing the project |
| `user_behavior_dataset.csv` | The dataset used in the analysis |

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/hamedallahodeh/Data-Visualization.git
   cd Data-Visualization
   ```
2. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```
3. Open the notebook and run all cells:
   ```bash
   jupyter notebook Data_Vis_Project.ipynb
   ```

> **Note:** Make sure the path in the notebook's `pd.read_csv(...)` cell points to `user_behavior_dataset.csv` in the same folder.
