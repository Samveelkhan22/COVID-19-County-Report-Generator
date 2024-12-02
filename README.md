# COVID-19 County Report Generator

This project is a Python-based tool designed to generate detailed COVID-19 reports for any county in the United States using data from [Johns Hopkins University's GitHub repository](https://github.com/CSSEGISandData/COVID-19). The program utilizes `pandas` and `geopandas` libraries to process and analyze real-world COVID-19 data.

## Features
- **Customizable Reports**: Provides COVID-19 statistics for a user-specified county.
  - Total new cases in 2021.
  - Average new cases in 2022.
  - Cumulative cases as of December 31, 2022.
- **Real Data**: Uses authentic and regularly updated COVID-19 data.
- **Formatted Outputs**: Generates user-friendly reports with properly formatted numerical values for better readability.

## Usage

- Open the Jupyter Notebook (covid.ipynb) in your Python environment.
- Run the notebook and follow the on-screen prompts to input the desired county name.
- View the generated report for the specified county directly in the output cell.

## Example Output

### For Montgomery County:

COVID-19 Report for Montgomery County
--------------------------------------
- Total new cases in 2021: 123,456
- Average new cases in 2022: 789
- Cumulative cases as of 12/31/22: 1,234,567

## Dependencies

- Python 3.x
- pandas
- geopandas


