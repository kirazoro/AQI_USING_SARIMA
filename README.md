
# AirWatch: Interactive Air Quality Monitoring System

## Project Overview
AirWatch is a comprehensive system for monitoring and forecasting air quality. It combines data analysis, machine learning, and interactive visualizations to provide actionable insights into air pollutant levels. This project aims to support environmental planning by predicting future trends and highlighting key pollutants' behaviors.

## Features
- **Data Visualization**: Explore pollutant trends through various charts, including time-series plots, heatmaps, and boxplots.
- **Machine Learning Forecasting**: Uses the ARIMA model to predict future pollutant levels with high accuracy.
- **Interactive Dashboard**: Built with Bokeh and Panel, it allows dynamic filtering and real-time data exploration.
- **Pollutant Coverage**: Tracks PM2.5, PM10, NO2, CO, O3, and SO2 concentrations.

## Dataset
- **Source**: Synthetic data for demonstration, or real-world data from platforms like OpenAQ, EPA, and Kaggle.
- **Time Range**: Covers daily pollutant readings from 2019 to 2024.
- **Preprocessing**: Includes handling missing values, ensuring stationarity, and normalizing data for analysis.

## Key Technologies
- **Python**: Primary language for data processing and modeling.
- **Libraries**:
  - `Pandas`, `NumPy` for data handling.
  - `Seaborn`, `Matplotlib`, `Plotly` for visualizations.
  - `Statsmodels` for ARIMA modeling.
  - `Bokeh`, `Panel` for building interactive dashboards.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AQi.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to analyze data and train the forecasting model.
4. Launch the interactive dashboard:
   ```bash
   panel serve --show dashboard.ipynb
   ```

## Results
- **Forecasting Accuracy**: Evaluated using Mean Squared Error (MSE) to ensure reliable predictions.
- **Visualization**: Clear and interactive plots for pollutant analysis.
- **Future Projections**: Provides 30-day pollutant forecasts for actionable insights.

## Future Enhancements
- **Advanced Models**: Implement SARIMA, LSTM, or Prophet for improved forecasting.
- **Weather Integration**: Incorporate weather data for more accurate pollutant predictions.
- **Deployment**: Plan to deploy the system as a publicly accessible web application.

## Contributing
Contributions are welcome! If you have suggestions for new features or improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any questions or feedback, reach out via email: [chitrangibhatnagar@gmail.com].

```
