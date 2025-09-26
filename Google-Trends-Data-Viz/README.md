# Google Trends Meets Real-World Data: A Data Storytelling Project

## Project Overview

This project explores the intriguing relationship between online search behavior, as captured by Google Trends, and real-world economic and financial indicators. We investigate whether the collective curiosity of internet users can offer insights into stock market movements, cryptocurrency price fluctuations, and even broader economic health, such as unemployment rates. Through data analysis and visualization, we aim to uncover compelling correlations and potential leading indicators that highlight the power of data storytelling.

## Key Investigations

Our analysis focuses on three primary case studies:

1.  **Tesla Stock Price vs. Google Searches for "Tesla"**: Examining if the popularity of searches for "Tesla" correlates with the company's stock performance.
2.  **Bitcoin Price vs. Google Searches for "Bitcoin"**: Investigating whether search interest in "Bitcoin" reflects its market price movements.
3.  **Unemployment Rate vs. Google Searches for "Unemployment Benefits"**: Exploring if spikes in searches for "Unemployment Benefits" can serve as an early signal or a concurrent indicator for official unemployment rates.

## The 2020 Spike: A New Era of Uncertainty

A significant part of this project delves into the impact of the COVID-19 pandemic, particularly the dramatic surge in unemployment during 2020. This period presented an unprecedented scenario where:

*   Web searches for "Unemployment Benefits" **skyrocketed**.
*   The official unemployment rate **spiked** at a speed and magnitude never before seen in modern U.S. history, far exceeding even the 2008 financial crisis.

This event serves as a stark reminder of how real-world crises can profoundly reshape data patterns, often in ways that traditional models struggle to predict.

## Key Learning Points & Takeaways

This project is not just about the findings but also about the journey of data analysis and visualization. Through its completion, we've reinforced and mastered several crucial data science skills:

*   **Data Exploration**: Efficiently understanding datasets using `.head()`, `.tail()`, and `.describe()`.
*   **Resampling**: Aligning time-series data frequencies (e.g., daily to monthly) for comparative analysis.
*   **Handling NaNs**: Identifying and managing missing values with `.isna().sum()`.
*   **Matplotlib Styling**: Crafting professional and insightful plots by customizing labels, limits, linewidths, colors, linestyles, and markers.
*   **Date Locators**: Implementing `YearLocator`, `MonthLocator`, and `DateFormatter` for precise timeline control in visualizations.
*   **Grids for Seasonality**: Utilizing visual grids to highlight and identify repeating patterns in time-series data.
*   **Rolling Averages**: Smoothing noisy data to reveal underlying trends and distinguish between leading and lagging indicators.
*   **Impact of New Data**: Observing how recent events, particularly those in 2020, significantly altered established patterns in unemployment and search data.

## Final Thoughts

Google Trends data offers more than just insights into search popularity; it provides a real-time pulse of collective human behavior. When integrated with traditional economic and financial datasets, it becomes a powerful instrument for:

*   **Detecting Leading Indicators**: Identifying potential early signals, such as search spikes preceding shifts in unemployment.
*   **Understanding Market Psychology**: Gaining insights into public sentiment and "mania" surrounding assets like Tesla or Bitcoin.
*   **Analyzing Societal Reactions**: Comparing and contrasting public responses during major crises (e.g., 2008 vs. 2020).

This project underscores the immense value of data storytelling—transforming raw numbers and charts into compelling narratives that connect directly with real-world events and human decisions.

## Getting Started

### Prerequisites

To run this project, you will need Python installed along with the libraries listed in `requirements.txt`.



### Usage

[Instructions on how to run your notebooks or scripts, e.g., "Open and run the Jupyter notebooks in `notebooks/` directory."]

## Project Structure

*   `data/`: Contains raw and processed data files (e.g., Google Trends data, stock prices, unemployment rates).
*   `notebooks/`: Jupyter notebooks detailing the analysis and visualizations for each case study.
*   `src/`: (Optional) Python scripts for data cleaning, analysis, or custom functions.
*   `README.md`: This file.
*   `requirements.txt`: List of project dependencies.

## License

[Specify your license here, e.g., MIT License]

## Acknowledgements

*   Google Trends for providing public search interest data.
*   [Any other data sources or inspirations]
