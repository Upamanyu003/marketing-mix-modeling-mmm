# Marketing Mix Modelling (MMM) Project

This repository contains a complete implementation of a **Marketing Mix Model (MMM)** developed using real-world datasets. The objective of this project is to measure the impact of various advertising channels on sales, model diminishing returns, and optimize marketing budget allocation using data-driven techniques.

##  Project Highlights

- **Adstock Transformation** – models carry-over effects of ads
- **Hill Saturation Function** – captures diminishing marketing returns
- **Ridge Regression** – resolves multicollinearity between channels
- **ROI Computation** – measures profitability of each channel
- **Linear Optimization** – reallocates budgets to maximize sales

##  Model Performance

- **Train R²:** 0.93  
- **Test R²:** 0.70  
The model generalises well, demonstrating strong predictive power.

## Key Insights

| Channel      | ROI      | Recommendation          |
|-------------|----------|-------------------------|
| Radio       | 62.9x    | Strong – increase spend |
| TV          | 38.1x    | Effective – maintain    |
| Internet    | 0.78x    | Near break-even – refine|
| SMS         | -175x    | Destroying value – stop |
| Newspaper   | -3068x   | Extremely wasteful      |

**Conclusion:** Media budget should be shifted from SMS and Newspaper to Radio and TV to maximise incremental sales.

##  Tech Stack

- Python (NumPy, Pandas, scikit-learn)
- PuLP (linear programming)
- Google Colab
- Matplotlib / Seaborn


