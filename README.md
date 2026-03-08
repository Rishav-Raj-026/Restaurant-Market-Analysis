# Metropolitan Restaurant Market Analysis

## Project Overview
This repository contains an exploratory data analysis (EDA) modeling the localized restaurant industry. Using synthetic, proprietary market data, this project evaluates pricing power, consumer sentiment via ratings, and segments high-performing establishments serving targeted strategic menu items.

## Business Objectives
* Assess the demographic spread of restaurant ratings to establish market satisfaction benchmarks.
* Analyze average pricing structures stratified by cuisine types.
* Isolate and profile top-tier establishments (Rating >= 4.0) that feature "Chocolate Cake" as a signature offering for potential targeted campaigns or partnerships.

## Methodology & Tech Stack
* **Language:** Python
* **Data Manipulation & Cleaning:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## Technical Execution
The analysis script handles end-to-end data processing:
1. **Data Generation:** Generates a robust mock dataset simulating 20 unique establishments with variables for pricing, ratings, reviewing volume, and signature items.
2. **Data Cleansing:** Simulates real-world data unreliability by structuring deliberate missing values (NaNs), subsequently resolving them utilizing mean and median imputation algorithms to preserve statistical validity without dropping observations.
3. **Exploratory Data Analysis:** Computes and ranks market leaders based on consumer satisfaction. Utilizes boolean masking to cross-filter strategic subsets.
4. **Data Visualization:** Generates production-ready reporting plots (histograms, bar charts, and scatter plots parameterized by review volume).

## Repository Contents
* `restaurant_market_analysis.ipynb`: The core analytical Jupyter Notebook containing all processing, analysis, and visualization logic.

## Usage
To execute the analysis locally:

```bash
git clone https://github.com/your-username/restaurant-market-analysis.git
cd restaurant-market-analysis
pip install pandas numpy matplotlib seaborn
jupyter notebook restaurant_market_analysis.ipynb
```

*Note: For privacy and confidentiality, the dataset utilized within this repository is algorithmically generated based on approximate market bounds and does not represent absolute, real-world patron or establishment data.*
