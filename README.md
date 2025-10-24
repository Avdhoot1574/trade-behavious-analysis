# Trader Behavior Analysis — Market Sentiment & Performance

## Overview
This project analyzes how trader performance (profitability, risk, volume, leverage) aligns with overall market sentiment (Fear vs Greed).  
The study combines trading data with sentiment classifications, applies exploratory data analysis (EDA), statistical validation, and regression modeling to uncover behavioral patterns and actionable trading strategies.

Key findings:
- Traders achieve higher profitability during Extreme Greed, especially with long positions.
- Fear phases drive larger trades and higher fees but with weaker returns.
- Short trades are relatively more effective in Fear, while long trades dominate in Greed.
- Elite traders capture the majority of profits, highlighting behavioral asymmetry.
- Statistical tests confirm significant differences in PnL across sentiment phases.

## Project Structure
ds_avdhoot/

├── notebook_1.ipynb # Main analysis (EDA, statistical validation, regression)

├── notebook_2.ipynb # (Optional) Additional experiments or model refinements

├── csv_files/ # Processed data and summary tables

│ └── sentiment_summary.csv

├── outputs/ # Visual outputs (charts, plots, images)

│ ├── pnl_by_sentiment.png

│ └── *.png / *.jpg

├── ds_report.pdf # Final detailed report with insights and strategies

└── README.md # Project overview and instructions


## How to Use

1. Open the notebooks in Google Colab (links below).  
2. Run cells sequentially to reproduce the analysis.  
3. Outputs (plots, CSVs) will be saved into the respective folders.  
4. Refer to `ds_report.pdf` for the final structured insights.


## Google Colab Links

- [notebook_1.ipynb](INSERT_PUBLIC_COLAB_LINK_HERE)  
- [notebook_2.ipynb](INSERT_IF_USED)  

Ensure sharing is set to “Anyone with the link can view”.


## Methods Applied

- Data Cleaning & Merging: Timestamp normalization, dataset alignment  
- Exploratory Data Analysis: Sentiment distribution, PnL by sentiment, long vs short, Pareto analysis  
- Statistical Validation: Kruskal–Wallis test, Dunn’s post-hoc analysis  
- Regression Modeling: OLS with sentiment, side, coin, trade size, leverage, fees, and time features  
- Visualization: Boxplots, violin plots, Pareto curves, distribution charts  

## Key Insights

- Sentiment-aware strategies outperform contrarian ones.  
- Greed phases: Long positions yield the strongest returns.  
- Fear phases: Overtrading reduces profitability; shorts are relatively stronger.  
- Elite traders dominate profits, suggesting discipline and sentiment awareness.  
- Sentiment is a context filter, not a standalone predictor — best used with technical indicators.

## Submission Notes

- All work executed in Google Colab.  
- Repository mirrors the required submission structure.  
- Final deliverables: `ds_report.pdf`, notebooks, CSV outputs, and visualizations.  
