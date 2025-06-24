# 🎬 Netflix Originals Data Analysis

This project involves an in-depth analysis of Netflix Originals using a public dataset. The goal is to extract meaningful insights and trends from the dataset using data preprocessing, feature engineering, and visualizations.

---

## 📁 Dataset

- Source: `NetflixOriginals.csv`
- Columns: Title, Genre, Premiere, Runtime, IMDB Score, Language

---

## 🔧 Data Preprocessing

1. **Upload Dataset**
2. **Date Standardization**: Converted the `Premiere` column to a uniform format (`YYYY-MM-DD`).
3. **Feature Engineering**:
   - Extracted **year**, **month**, and **day** from the date column.
   - Created new columns as required for deeper analysis.
4. **Null Check**: Verified there are no missing or empty fields.
5. **Note**: Since prediction is not involved, outliers are **not removed**.

---

## 🎯 Objectives & Insights

| # | Question | Solution Summary |
|--|----------|------------------|
| 1 | In which language were the long-running films created? | ✅ Visualized with bar graph |
| 2 | Find & visualize IMDB scores of 'Documentary' films between Jan 2019–June 2020 | ✅ Filtered by date & genre, visualized using scatter plot |
| 3 | Which genre has the highest IMDB rating among English films? | ✅ Grouped by genre and sorted |
| 4 | What is the average runtime of movies in Hindi? | ✅ Used mean aggregation |
| 5 | How many unique genres are there and what are they? | ✅ Counted and visualized using pie chart |
| 6 | Top 3 most used languages | ✅ Bar chart of most frequent languages |
| 7 | Top 10 Movies by IMDB Rating | ✅ Sorted and visualized |
| 8 | Correlation between IMDB Score and Runtime | ✅ Calculated and plotted scatter + regression |
| 9 | Top 10 Genres by IMDB Score | ✅ Grouped by genre, visualized using bar chart |
| 10 | Top 10 Movies with Highest Runtime | ✅ Sorted and visualized |
| 11 | Year with Most Releases | ✅ Counted and plotted using bar graph |
| 12 | Are there outliers in the dataset? | ✅ Visualized using boxplots |

---

## 📊 Visualizations Used

- **Bar Charts**
- **Pie Charts**
- **Box Plots**
- **Scatter Plots**
- **Subplots**
- **Heatmaps**
- **Interactive Graphs using Plotly**

Libraries used:
- `pandas`, `numpy`
- `matplotlib.pyplot`, `seaborn`
- `plotly.express`

---

## 🧠 Analysis Methodology

1. **Feature Selection & Grouping**:
   - Used `.groupby()`, `.sort_values()`, and `.value_counts()` to prepare analytical datasets.
2. **Visualization**:
   - Used multiple Python libraries to create meaningful and interactive charts for deeper insight.

---

## 📌 Conclusion

This project demonstrates the power of EDA (Exploratory Data Analysis) in discovering trends and patterns in entertainment content. Without any predictive modeling, we’ve still extracted strong business insights from raw data.

---

## 🧾 Author

**Abhay Gupta**  
B.Tech CSE, LNMIIT Jaipur  
2025 Graduate  
