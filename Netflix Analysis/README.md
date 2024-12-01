
# 📊 Netflix Titles Analysis

### A data analysis project exploring trends and patterns in Netflix's movie and TV show catalog.

## 📝 Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Objective](#objective)
4. [Process](#process)
5. [Results](#results)
6. [Technologies Used](#technologies-used)
7. [Future Work](#future-work)
8. [How to Run](#how-to-run)

---

## 📚 Introduction
Netflix is one of the largest streaming platforms in the world, offering a wide variety of movies and TV shows. This project uses a dataset of Netflix titles to analyze trends in its content catalog, including:
- The distribution of movies vs. TV shows.
- Content trends over time.
- Popular genres and top content-producing countries.

---

## 📁 Dataset
- **Source**: [Netflix Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Description**: Contains information about Netflix's movies and TV shows, including:
  - Title
  - Genre
  - Release Year
  - Country
  - Date Added to Netflix
  - Type (Movie/TV Show)

---

## 🎯 Objective
The goal of this project is to explore the Netflix catalog through **exploratory data analysis (EDA)** and uncover:
- Patterns in content distribution.
- Trends in content addition over the years.
- Insights into the most popular genres and countries producing content.

---

## 🔍 Process
1. **Data Cleaning**:
   - Handled missing values.
   - Converted dates to proper datetime format.
   - Removed unnecessary whitespace in columns.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed trends in the number of movies and TV shows.
   - Visualized popular genres and top content-producing countries.
   - Explored the addition of content over time.

3. **Data Visualization**:
   - Used Seaborn and Matplotlib (with `fivethirtyeight` style) to create informative visualizations.

---

## 📈 Results
Here are some key insights from the analysis:
- **Movies dominate the Netflix catalog**, comprising approximately X% of all content.
- **Content growth accelerated after 2015**, with a peak in the number of titles added in 20XX.
- **Top Genres**: Drama and Comedy are the most common genres on Netflix.
- **Top Countries**: The majority of Netflix's content originates from the United States, followed by X and Y.

---

## 🛠 Technologies Used
- **Python**: Data manipulation and analysis.
- **Jupyter Notebook**: For code and documentation.
- **Libraries**:
  - `pandas` for data cleaning and manipulation.
  - `matplotlib` and `seaborn` for visualization.

---

## 🚀 Future Work
- Include predictive modeling to forecast future trends in Netflix's catalog.
- Incorporate additional datasets (e.g., IMDb ratings or viewer statistics) for deeper analysis.
- Build an interactive dashboard using Tableau or Power BI.

---

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/netflix-analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd netflix-analysis
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook netflix_analysis.ipynb
   ```
