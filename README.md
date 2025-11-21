# COVID-19 Data Analysis Project
# Assignment 5
## 📌 Project Overview
This project analyzes the impact of COVID-19 across different countries and explores the relationship between the spread of the virus and world happiness indicators (GDP, Social Support, etc.).

## 🛠️ Technologies Used
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** Pandas, Numpy, Seaborn, Matplotlib

## 📊 Methodology
1.  **Data Collection:** Used COVID-19 confirmed cases dataset and Worldwide Happiness Report dataset.
2.  **Data Cleaning:** Dropped unnecessary columns (Latitude, Longitude) and aggregated data by country.
3.  **Feature Engineering:** Calculated the **Maximum Infection Rate** for each country by finding the maximum daily increase in cases (first derivative).
4.  **Data Merging:** Combined the COVID-19 data with the Happiness Report using an inner join.
5.  **Visualization:** Created scatter plots and regression plots to analyze correlations.

## 🔍 Key Findings
* **GDP vs Infection Rate:** There is a positive correlation between GDP per capita and the maximum infection rate. Developed countries with higher GDP initially showed higher infection reporting rates.
* **Social Support:** A similar positive correlation was observed between social support and infection spread.

## 📂 How to Run
1.  Download the `.ipynb` file and the CSV datasets.
2.  Open the notebook in Jupyter or Google Colab.
3.  Run the cells sequentially to see the analysis and graphs.
