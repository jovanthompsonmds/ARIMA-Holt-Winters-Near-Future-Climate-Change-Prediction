# ARIMA Holt-Winters Near Future Climate Change Prediction

## Overview
This project focuses on predicting daily average temperatures using ARIMA and Holt-Winters models, leveraging historical data from 1980 to 2010. The predictions span from 2010 to 2020, extending to 2030, providing valuable insights into near-future climate trends and potential anomalies.

## Features
- **Time Series Analysis**: Explore historical temperature data to detect seasonal patterns and long-term trends.
- **Predictive Modeling**: Use ARIMA and Holt-Winters methods for accurate temperature forecasting.
- **Data Visualization**: Generate decomposition plots, moving averages, and confidence intervals to assess trends and variability.
- **Ethical Insights**: Discuss implications for climate policy and public health through an ethical lens.

## Files
1. `ARIMA Holt-Winters Near Future Climate Change Prediction.ipynb`  
   - Jupyter Notebook containing the complete analysis, forecasting, and visualizations.
   
2. `new_train.csv`  
   - Training dataset with daily average temperatures from 1980 to 2010.
   
3. `new_test.csv`  
   - Testing dataset (2010–2020) with missing temperature values.
   
4. `sample_submission.csv`  
   - Template for submitting forecasted temperatures.

## Requirements
- R (3.6 or higher)
- Required R packages:
  - `forecast`
  - `tsutils`
  - `ggplot2`
  - `lmtest`
  - `dplyr`
  - `lubridate`

Install the packages using:
install.packages(c("forecast", "tsutils", "ggplot2", "lmtest", "dplyr", "lubridate"))

## Usage
1. Clone the repository:
   git clone https://github.com/jovanthompsonmds/ARIMA-Holt-Winters-Near-Future-Climate-Change-Prediction.git
2. Navigate to the project directory: 
   cd Near-Future-Climate-Change-Prediction
3. Open the R Jupyter Notebook:
   jupyter notebook "Near Future Climate Change Prediction.ipynb"
4. Run the analysis to preprocess data, build models, and generate forecasts.

## Insights
This project helps in:
- Trend Analysis: Highlights long-term warming trends.
- Seasonal Patterns: Identifies consistent temperature cycles.
- Policy Implications: Supports climate adaptation and mitigation strategies.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request with improvements or new features.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
Developed by Jovan Thompson as part of a data science portfolio project.
