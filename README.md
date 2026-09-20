# 🏏 IPL 2025 – Exploratory Data Analysis

An end-to-end exploratory data analysis (EDA) of the IPL 2025 season, built with Python. This project digs into team performance, toss trends, player stats, and venue patterns to uncover the story behind the season's numbers.

## 📌 Project Overview

The notebook walks through the full analysis pipeline:

- Loading and inspecting the dataset
- Handling missing values
- Answering key questions about team and match outcomes
- Analyzing individual player performances (batting & bowling)
- Studying venue-wise match distribution
- Deriving custom insights beyond the obvious stats

## 🛠️ Tools & Libraries

- **Python**
- **Pandas** & **NumPy** – data manipulation
- **Seaborn** & **Matplotlib** – data visualization
- **Jupyter Notebook**

## 📊 Key Insights

| Question | Insight |
|---|---|
| Most match wins | Royal Challengers Bengaluru (11 wins) |
| Toss winner = match winner | ~58.11% of matches |
| Highest individual score | Abhishek Sharma – 141 runs |
| Top run-scorers | KL Rahul, N Pooran |
| Best bowling figures | Mitchell Starc & Hardik Pandya – 5 wickets each |
| Most matches hosted | Narendra Modi Stadium, Ahmedabad (9 matches) |
| Highest winning margin (runs) | Sunrisers Hyderabad – won by 110 runs |

## 📂 Project Structure

```
├── IPL_2025.ipynb      # Main analysis notebook
├── IPL_2025.csv         # Dataset (season match data)
└── README.md            # Project documentation
```

## 🔍 Analysis Sections

1. **Data Loading & Cleaning** – handling nulls in scores, wickets, and match outcomes
2. **Team Performance** – wins by team, toss decision trends, toss-vs-match-winner relationship
3. **Player Performances** – Player of the Match leaders, top scorers, best bowling figures
4. **Venue Analysis** – most-used venues of the season
5. **Custom Insights** – highest winning margin, top individual score, best bowling performance

## 🚀 How to Run

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install pandas numpy seaborn matplotlib
   ```
3. Open the notebook:
   ```bash
   jupyter notebook IPL_2025.ipynb
   ```

## 📈 Sample Visualizations

The notebook includes bar plots and count plots for:
- Total matches won per team
- Toss decision trends
- Match outcome by runs vs. wickets
- Top 10 Player of the Match award winners
- Top run-scorers and wicket-takers
- Most-used venues

## 🤝 Contributing

Feel free to fork this repo, raise issues, or suggest additional questions/insights worth exploring in the dataset.

## 📄 License

This project is open-sourced for educational and portfolio purposes.
