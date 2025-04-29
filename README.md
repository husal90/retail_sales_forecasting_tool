# Retail Sales Forecasting Tool

A standalone browser-based application for retail sales forecasting and analysis. This tool helps retail businesses predict future sales trends using historical data, with no server-side processing required.

## Features

### Data Management
- **CSV Upload**: Import your sales data from CSV files with flexible column mapping
- **Sample Data**: Test the application with built-in sample data
- **Automatic Detection**: Handles different column names (sales/revenue, month/period/date)

### Forecasting Engine
- **Customizable Forecasts**: Set forecast length (1-12 periods)
- **Adjustable Parameters**: 
  - Smoothing factor
  - Seasonality detection and inclusion
  - Trend analysis and projection
- **Confidence Intervals**: Visualize upper and lower forecast bounds

### Visual Analytics
- **Interactive Charts**: View historical and forecast data
- **Pattern Recognition**: Analyze seasonal patterns with radar charts
- **Trend Analysis**: Linear regression trend line visualization
- **Key Performance Indicators**: Total sales, monthly averages, peak periods

### Export Options
- **CSV Export**: Download forecast data in CSV format
- **Report Generation**: Create detailed HTML reports with charts and analysis

## How It Works

The forecasting tool uses several statistical methods:

1. **Exponential Smoothing**: Applies weighted averages to historical data, giving more importance to recent data points
2. **Seasonality Detection**: Identifies repeating patterns in your data (monthly, quarterly)
3. **Trend Analysis**: Analyzes the overall direction of your sales data
4. **Confidence Intervals**: Calculates prediction ranges based on historical volatility

## Getting Started

### Installation

No installation required! Simply download the HTML file and open it in any modern web browser.

```bash
git clone https://github.com/husal90/retail-sales-forecasting.git
cd retail-sales-forecasting
```

Then open `retail_sales_forecasting_tool.html` in your browser.

### Usage

1. **Data Upload Tab**
   - Upload your sales data CSV or use the sample data
   - Preview your data in both chart and table formats

2. **Forecast Tab**
   - Set your forecast parameters (periods, smoothing factor, seasonality, trend)
   - Generate the forecast to see predictions with confidence intervals

3. **Analysis Tab**
   - View detailed sales metrics and visualizations
   - Analyze seasonal patterns and long-term trends

4. **Export Tab**
   - Download your forecast data as CSV
   - Generate a comprehensive HTML report

## CSV Format

Your CSV file should contain at least two columns:
- A time period column (month, date, period, time, etc.)
- A sales value column (sales, revenue, amount, value, etc.)

Example:
```
month,sales
Jan,12000
Feb,15000
Mar,18000
```

## Browser Compatibility

Tested and working in:
- Chrome 89+
- Firefox 86+
- Edge 89+
- Safari 14+

## Dependencies

This project uses the following libraries (included via CDN):
- [Chart.js](https://www.chartjs.org/) - For data visualization
- [PapaParse](https://www.papaparse.com/) - For CSV parsing

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Roadmap

- Add multiple forecasting algorithms
- Support for multi-variable forecasting
- Dark mode theme
- Save/load forecast projects
- Anomaly detection in historical data

## Author

GitHub: [@husal90](https://github.com/husal90)
