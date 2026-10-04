# Mobile Device Usage and User Behavior Analysis

Data visualization project for my university course.

Student: Hamedallah Anwer Hamedallah Issa
Student ID: 320220603007

## About the project

In this project I looked at a dataset of mobile phone users (700 rows) and made some charts to understand how people use their phones, like which devices are most common, how screen time changes with age, and which devices use the battery better.

## Dataset

I used the "Mobile Device Usage and User Behavior Dataset" from Kaggle:
https://www.kaggle.com/datasets/valakhorasani/mobile-device-usage-and-user-behavior-dataset

It has info about each user such as device model, operating system, app usage time, screen on time, battery drain, number of apps, data usage, age, gender and a user behavior class.

## What's in the notebook

- Most popular device models
- Screen time by age, split by gender
- Average data usage for each age group
- Battery efficiency for each device (battery drain divided by screen time)
- Top 5 users by app usage time

## Files

- `Data_Vis_Project.ipynb` - the code and charts
- `Data_Vis_project.pptx` - the presentation
- `user_behavior_dataset.csv` - the dataset

## Running it

I used Python with pandas, matplotlib and seaborn. To run the notebook:

```
pip install pandas matplotlib seaborn jupyter
jupyter notebook Data_Vis_Project.ipynb
```

Make sure the CSV file is in the same folder as the notebook.
