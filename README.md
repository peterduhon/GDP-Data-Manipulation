# GDP-Data-Manipulation
This project analyzes the GDP data of the top 10 economies in the world. It includes data processing, visualization, and export functionalities using Python, pandas, numpy, and matplotlib.
## Features
- Loads and processes GDP data for top 10 economies
- Converts GDP values from billions to trillions of USD
- Maps country names to ISO 3166-1 alpha-2 country codes
- Creates a bar plot visualization of GDP data
- Exports processed data to CSV files

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib

## Usage
1. Run `gdp_analysis.py` to process the data and generate visualizations.
2. The script will create two CSV files:
   - `Largest_economies.csv`: Contains the processed GDP data
   - `Largest_economies_with_codes.csv`: Includes country codes and sorted data

## Data Visualization
The script generates a bar plot showing the GDP of top 10 economies, using country codes for easy readability.

## Future Improvements
- Integration with live API data sources
- Additional data visualizations
- Time series analysis of GDP data

## Author
Pete Duhon

## License
This project is open source and available under the [MIT License](LICENSE).
