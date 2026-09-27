# Kenyan climate time-series analysis

An exploratory R Markdown notebook using monthly Kenyan temperature and rainfall data. It cleans dates and column names, visualises seasonal patterns, and compares several forecasting approaches.

## Contents

- `Kenyan_avg_monthly_temp_timeseries.Rmd`: source notebook for data preparation, charts, model fitting, and comparisons.
- `Kenyan_avg_monthly_temp_timeseries.nb.html`: rendered notebook.
- `kenya-climate-data-1991-2016-temp-degress-celcius.csv` and `kenya-climate-data-1991-2016-rainfallmm.csv`: source data used by the notebook.
- PNG files: selected fitted-versus-actual and forecasting figures.

The notebook uses R packages including tsibble/fpp3, ggplot2, forecast, Prophet, and Keras/TensorFlow through R. It explores ETS, ARIMA, Prophet, and LSTM approaches. These are exploratory comparisons, not a production forecast or a claim of predictive performance.

## Reproduce

Open the R Markdown file in RStudio, install the packages listed in its setup chunk, and run or knit it from this repository directory so the relative CSV paths resolve. Some model sections have substantial package and compute requirements. Read the notebook's code and assumptions before reusing any forecast.
