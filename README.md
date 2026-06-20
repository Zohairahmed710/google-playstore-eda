# Google Play Store Apps – Exploratory Data Analysis

## Goal
To analyse a real‑world, messy dataset of over 10,000 Google Play Store apps and find out:
- What factors affect an app’s rating?
- Do paid apps have higher ratings?
- Is there a relationship between app size, installs, and content rating?

## Tools Used
- Python (Pandas, NumPy)
- Data Visualization (Matplotlib, Seaborn)
- Statistics (SciPy – t‑test, correlation, chi‑square)
- Jupyter Notebook (Google Colab)

## What I Did
1. **Cleaned the data** – handled missing values, converted messy columns (`Installs`, `Size`, `Price`) into numeric types.
2. **Visualised patterns** – created bar charts, scatter plots, box plots, and a top‑10 installed apps chart.
3. **Performed statistical tests**:
   - **t‑test:** Paid apps have a significantly higher average rating than free apps (p = 0.0003).
   - **Correlation:** Rating and Installs are almost unrelated (r = 0.051). A high rating doesn’t guarantee downloads.
   - **Chi‑square test:** Content Rating (Everyone, Teen, etc.) is strongly associated with whether an app is Free or Paid (p < 0.0001).

## Key Insights
- Ratings are consistent across categories (~4.2–4.3).
- Paid apps are rated slightly better, but price alone doesn't predict a higher rating.
- App size has only a weak positive correlation with installs.
- Apps rated for “Everyone” have the highest median installs.
- Recently updated apps tend to have slightly higher ratings.

## About Me
I’m a 16‑year‑old self‑taught data analyst from Pakistan, learning Python, statistics, and machine learning to build a freelance career.  
This is my second public portfolio project.

## Links
- [Kaggle Notebook](#) ()
- [Titanic EDA Repository](#https://github.com/Zohairahmed710/titanic-eda) (add your link)
