# -gym-exercise-analysis-
Analyzing gym exercise data to identify highly rated beginner-friendly workouts using Python and data visualization.
# Gym Exercise Analysis
## Overview
This project analyzes a gym exercise dataset to identify highly rated beginner-friendly exercises for specific muscle groups. Using Python and data analysis techniques, the notebook filters exercises by body part, experience level, and user ratings to help highlight effective workout options for beginners.
This project uses the Gym Exercise Dataset available on Kaggle.

Source:
https://www.kaggle.com/datasets/niharika41298/gym-exercise-data

The dataset contains exercise information including:
- Exercise title
- Body part targeted
- Difficulty level
- Ratings and descriptions
- Exercise details
## Objectives
- Explore a gym exercise dataset
- Filter exercises by targeted muscle groups
- Identify beginner-level exercises
- Analyze exercise ratings
- Visualize highly rated workout recommendations

## Dataset Features

The dataset includes information such as:

- Exercise Title
- Body Part Targeted
- Difficulty Level
- User Rating
- Rating Description

## Analysis Performed

### Data Preparation
- Loaded the exercise dataset
- Selected relevant columns for analysis
- Cleaned and organized the data

### Exercise Filtering
The notebook focuses on exercises targeting:

- Abdominals
- Biceps
- Quadriceps

Additional filters were applied to identify:

- Beginner-level exercises
- Exercises with ratings above 6.9

### Visualization
A bar chart was created to compare ratings among selected quadriceps exercises, making it easier to identify highly rated beginner-friendly options.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Key Takeaways

This analysis demonstrates how data filtering and visualization can be used to identify workout recommendations based on specific fitness goals and experience levels. By narrowing exercises to beginner-friendly, highly rated options, users can make more informed training decisions.

## How to Run

1. Clone this repository.
2. Install the required packages.

```bash
pip install pandas matplotlib
