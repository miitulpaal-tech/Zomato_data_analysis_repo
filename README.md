# Zomato Data Cleaning & Dashboard Project

I cleaned a raw dataset of Zomato restaurants to make it ready for analysis, and then built an interactive Tableau dashboard to help find the best spots and prices for opening a new restaurant.

## What Was Done

* **Data Cleaning (Python):** * Removed duplicate rows and dropped columns that weren't useful.
  * Cleaned up missing/null values and fixed text formatting (like text fixes in cuisines and costs).
  * Converted data types (like changing ratings and costs from strings to numbers) using Pandas and NumPy.
   

* **Data Visualization (Tableau Dashboard):**
  * **Live Dashboard Link:** [View my Tableau Dashboard](https://drive.google.com/file/d/1TqQXH7Ikpv6hK8YWoN3_vMEAL1HscvrC/view?usp=sharing)
  * Created an **Executive KPI Header** tracking the total number of restaurants analyzed, average ratings, and average costs.
  * Built a **Geography of Opportunity Map** using location bar charts and bivariate ratings filters to spot neighborhoods with low competition but high ratings.
  * Designed a **Price vs. Quality Scatter Plot** (scaled by total votes) to identify the pricing "sweet spot" for high consumer engagement.
  * Added a **Cuisine Density Treemap** to easily see the most popular and highly-rated food types at a glance.
  * Enabled interactive **Cross-Chart Actions** so clicking on any location automatically updates all other charts for deep exploratory analysis.

## Tools Used
* **Data Prep:** Python (Pandas, NumPy)
* **Visualization:** Tableau Public

## Project Files
* [Original Dataset Link](https://drive.google.com/file/d/1CjmaQcCJlnIPs928Z6CBqKL8braB_fiO/view?usp=sharing) — The raw, uncleaned data
* [Cleaned Dataset Link](https://drive.google.com/file/d/1GZZNUb2nqOkvC5d94r8T7PpcJ50UjfgQ/view?usp=sharing) — The final processed data
* `ZOMATO.ipynb` — The Jupyter notebook showing all my cleaning steps code

## Author
**Mitul** 
