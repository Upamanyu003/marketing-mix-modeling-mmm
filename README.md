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

##  Project Conclusion

This project demonstrates how data-driven Marketing Mix Modelling (MMM) can quantify the true impact of advertising channels on business performance. By incorporating **Adstock transformation** to capture carry-over advertising effects, **Hill saturation** to model diminishing returns, and **Ridge Regression** to address multicollinearity, the model achieved strong predictive power (Train R²: 0.93, Test R²: 0.70).

The results revealed that **Radio and TV** are high-return channels, with ROIs of **62.9x** and **38.1x**, respectively, while **Newspaper** and **SMS** campaigns produce negative returns, resulting in a loss of value. A linear programming optimisation model reallocated the same historical budget toward profitable channels, resulting in a substantial increase in projected incremental sales without increasing total spend.

This end-to-end analytics solution demonstrates how advanced statistical modelling and optimisation techniques can be used not only to measure marketing effectiveness but also to drive actionable business decisions. The methodology is scalable and can be deployed for annual planning, media mix experimentation, and performance forecasting in real-world marketing environments.

