# 🎬 Movie Dataset Analysis

## 📌 Overview
This project explores a dataset of *4,000 movies* spanning from 1980 to 2001. It includes key attributes like *genre, rating, IMDb score, votes, budget, gross earnings, runtime, and more. The goal is to perform **Exploratory Data Analysis (EDA)* to uncover trends in audience preferences, financial performance, and movie characteristics.

---

## 📂 Dataset Details
- *Filename:* movies_updated.csv  
- *Rows:* 4000  
- *Columns:* 15  

### 🔤 Column Descriptions

| Column     | Description |
|------------|-------------|
| name     | Movie title |
| rating   | Film rating (e.g., PG, R) |
| genre    | Primary genre |
| year     | Release year |
| released | Release date |
| score    | IMDb score |
| votes    | Number of IMDb votes |
| director | Director name |
| writer   | Writer name |
| star     | Lead actor/actress |
| country  | Country of production |
| budget   | Budget (USD) |
| gross    | Gross earnings (USD) |
| company  | Production company |
| runtime  | Duration in minutes |

---

## 🛠 Tools & Libraries
- *Python* (pandas, numpy, matplotlib, seaborn)
- *Jupyter Notebook* for interactive analysis
- *Data Cleaning*: type conversion, missing value handling
- *Visualization*: bar charts, scatter plots, boxplots, heatmaps

---

## 📊 Analysis Workflow

### 1. Data Cleaning
- Removed trailing commas from runtime and converted to float
- Checked for missing values and standardized formats
- Ensured numeric columns (budget, gross, votes, score) were properly typed

### 2. Exploratory Data Analysis
- Genre-wise vote distribution
- Budget vs. Gross comparison
- IMDb score trends
- Runtime distribution
- Top directors, stars, and production companies

---

## 🔑 Key Insights

- 🎭 *Drama dominates*: Drama received the highest number of IMDb votes, showing its broad audience appeal.  
- 🕵 *Crime & Mystery engage strongly*: These genres also attracted high engagement, reflecting audience interest in suspense-driven stories.  
- 🎶 *Niche genres*: Music and Western films had the fewest votes, suggesting smaller but dedicated fan bases.  
- 💰 *Budget ≠ Success*: Some lower-budget films achieved high gross earnings, while certain high-budget films underperformed.  
- ⭐ *Star power matters*: Movies featuring well-known directors and actors often scored higher and attracted more votes.  
- 📈 *Scores & Votes correlate*: Higher IMDb scores generally aligned with more votes, indicating that critically well-received films also drew larger audiences.

## 🚀 How to Run

1. Clone the repository:
   bash
   git clone https://github.com/your-username/movie-eda.git
   

2. Install required libraries:
   bash
   pip install pandas matplotlib seaborn
   

3. Launch the notebook:
   bash
   jupyter notebook Movie_EDA.ipynb
   

---
## 🔮 Future Enhancements
- Predict box office success using regression models
- Build interactive dashboards with Plotly or Streamlit
- Expand dataset with post-2001 movies and streaming data
