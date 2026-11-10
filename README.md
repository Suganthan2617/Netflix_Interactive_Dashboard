# Netflix Interactive Dashboard 📊

An interactive dashboard built using Python, Pandas, and Plotly to explore Netflix Movies and TV Shows data.

## Project Overview

This project transforms the static Netflix EDA from Task 1 into an interactive dashboard that allows users to explore content distribution, release trends, movie durations, and other patterns.

## Technologies Used

- Python
- Pandas
- NumPy
- Plotly
- Jupyter Notebook

## Dashboard Features

The dashboard includes six different chart types:

1. **Donut Chart:** Movies vs TV Shows distribution.
2. **Line Chart:** Netflix content additions over the years.
3. **Histogram:** Distribution of movie durations.
4. **Box Plot:** Movie duration by content rating.
5. **Scatter Plot:** Movie release year vs duration.
6. **Heatmap:** Monthly content additions by year.

### Interactive Features

- Hover tooltips for detailed chart information.
- Zooming and panning.
- Dropdown filter for All Content, Movies, and TV Shows.
- Standalone HTML dashboard for browser access.

## Dataset

Netflix Movies and TV Shows dataset from Kaggle:

https://www.kaggle.com/datasets/shivamb/netflix-shows

The dataset is not included in this repository. Download it and place `netflix_titles.csv` in the project folder before running the notebook.

## How to Run

1. Clone this repository.
2. Install the required libraries:

   `pip install pandas numpy plotly ipykernel jupyter`

3. Download the Netflix dataset and place it in the project folder.
4. Open `Netflix_Dashboard.ipynb` in Jupyter Notebook or VS Code.
5. Run all notebook cells in order.

## Dashboard Access

Open `dashboard.html` in a web browser to explore the interactive dashboard without running the notebook.

## Project Structure

```text
Netflix_Interactive_Dashboard/
├── Netflix_Dashboard.ipynb
├── dashboard.html
├── README.md
└── .gitignore
```

## Internship

Completed as part of the Python & Pandas EDA internship at Valentius Kryptix.

## Author

Suganthan S

GitHub: https://github.com/Suganthan2617