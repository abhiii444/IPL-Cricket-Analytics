# IPL-Cricket-Analytics
Advanced IPL Cricket Analytics Project using Python, Machine Learning, Data Visualization, and Statistical Analysis to uncover match-winning insights from ball-by-ball IPL data.
# IPL Cricket Analytics Project

## Project Overview

This project performs advanced analytics on historical IPL (Indian Premier League) cricket data using Python, Machine Learning, and Data Visualization techniques. The analysis focuses on uncovering insights related to team performance, batting trends, bowling efficiency, toss impact, venue behavior, player consistency, and match-winning patterns using ball-by-ball IPL datasets.

The project also includes a Machine Learning model to predict IPL match winners based on historical match features.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Machine Learning
- Exploratory Data Analysis (EDA)

---

## Dataset Information

The project uses:
- `matches.csv`
- `deliveries.csv`

Datasets contain:
- Match-level IPL information
- Ball-by-ball IPL delivery data
- Team statistics
- Venue information
- Toss decisions
- Player performances

---

## Project Workflow

### 1. Data Collection
- Imported IPL datasets
- Loaded match-level and ball-by-ball data

### 2. Data Cleaning
- Handled missing values
- Standardized team names
- Created derived features

### 3. Feature Engineering
Created advanced cricket KPIs such as:
- Total Runs
- Boundary Percentage
- Dot Ball Percentage
- Match Phase Analysis
- Strike Rate
- Economy Rate

### 4. Exploratory Data Analysis
Performed:
- Team performance analysis
- Batting analysis
- Bowling analysis
- Toss impact analysis
- Venue analysis
- Chasing vs defending analysis
- Player consistency analysis

### 5. Machine Learning
Built a Random Forest Classifier to predict IPL match winners using:
- Team names
- Toss winner
- Toss decision
- Venue

### 6. Data Visualization
Created multiple visualizations including:
- Bar Charts
- Pie Charts
- Line Charts
- Correlation Heatmaps
- Feature Importance Graphs
- Confusion Matrix

---

## Key Insights

- Teams chasing targets have higher win percentages.
- Death overs contribute the highest scoring intensity.
- Toss decisions significantly influence match outcomes.
- Certain teams heavily depend on star batters.
- Venue conditions strongly impact team performance.
- Bowlers with higher dot-ball percentages create stronger pressure.

---

## Machine Learning Model

### Model Used
- Random Forest Classifier

### ML Workflow
- Data preprocessing
- Label encoding
- Train-test split
- Model training
- Prediction
- Accuracy evaluation
- Feature importance analysis

---

## Project Structure

```bash
IPL-Cricket-Analytics/
│
├── dataset/
│   ├── matches.csv
│   └── deliveries.csv
│
├── notebook/
│   ├── ipl_analysis.ipynb
│   └── ipl_analysis.py
│
├── screenshots/
│
├── README.md
└── requirements.txt
```

---

## Screenshots

### Team Wins Analysis

![Team Wins](screenshots/team_wins.png)

---

### Top Run Scorers

![Top Batters](screenshots/top_batsmen.png)

---

### Top Wicket Takers

![Top Bowlers](screenshots/top_bowlers.png)

---

### Correlation Heatmap

![Heatmap](screenshots/heatmap.png)

---

### Feature Importance Analysis

![Feature Importance](screenshots/feature_importance.png)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/IPL-Cricket-Analytics.git
```

Install required libraries:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook or Google Colab notebook.

---

## Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## Future Improvements

- Power BI Dashboard
- Streamlit Deployment
- Live IPL API Integration
- Win Probability Prediction
- Advanced Deep Learning Models

---

## Conclusion

This project demonstrates an end-to-end Data Analytics and Machine Learning workflow using real-world IPL cricket datasets. It combines statistical analysis, feature engineering, visualization, and predictive modeling to generate actionable cricket analytics insights.

---

## Author

Abhishek Rawat
