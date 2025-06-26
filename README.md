# Google Play Store Analysis

This repository contains a series of Jupyter Notebook tasks focused on analyzing data from the Google Play Store. The tasks include data cleaning, visualizations, and advanced analytics to uncover key insights from app data.


## 📚 Table of Contents

- [Files in this Repository](#files-in-this-repository)
- [Key Highlights](#key-highlights)
- [Tools Used](#tools-used)
- [How to Run](#how-to-run)
	


## 📁 Files in this Repository


- `task1.ipynb`: Visualizes the **sentiment distribution** (positive, neutral, negative) of user reviews using a **stacked bar chart**,
   segmented by rating groups (e.g., 1–2 stars, 3–4 stars, 4–5 stars).
   Focuses only on apps with over 1,000 reviews and highlights the **top 5 app categories**.


- `task2.ipynb`: Creates a **dual-axis chart** to compare average installs and revenue between **free vs. paid apps** within the top 3 categories.
   Applies multiple filters such as minimum installs (10,000), revenue ($10,000), Android version (>4.0), size (>15MB), content rating ('Everyone'), 
   and app name length (≤30 characters).


- `task3.ipynb`: Plots a **bubble chart** analyzing the relationship between **app size** and **average rating**, 
   with bubble size representing the number of installs. Includes filters for rating (>3.5), 
   **Games** category, installs (>50k), and ensures the chart operates within a **12 PM to 4 PM** time window.




## 🔍 Key Highlights

- Cleaned and prepared app data by handling duplicates, missing values, and formatting
- Created various plots (bar charts, histograms, and comparisons) in Tasks 1 and 2 to identify trends
- Visualized user sentiment and category-wise performance with advanced charts in Task 3
- Applied filters to analyze specific app groups (e.g., by category, install count, and rating)



## 🛠️ Tools Used

- Python
- Jupyter Notebook
- pandas, matplotlib, seaborn, plotly
- nltk (for sentiment analysis)


## ✅ How to Run

You can open any of the `.ipynb` files in Jupyter Notebook or VS Code. Ensure you have the required libraries installed before running.

