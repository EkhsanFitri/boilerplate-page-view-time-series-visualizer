# Page View Time Series Visualizer

This is the boilerplate for the Page View Time Series Visualizer project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/page-view-time-series-visualizer

This project visualizes time series data from the freeCodeCamp forum, showing daily page views from 2016-05-09 to 2019-12-03.

## Features

- **Line Plot:** Daily page views over time.
- **Bar Plot:** Average daily page views for each month grouped by year.
- **Box Plots:** Distribution of page views by year and by month.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn

## Usage

1. Clone the repository.
2. Install dependencies:
   ```
   pip install pandas matplotlib seaborn
   ```
3. Run the main script to generate plots and run tests:
   ```
   python main.py
   ```
4. Generated plots will be saved as `line_plot.png`, `bar_plot.png`, and `box_plot.png`.

## Data Cleaning

- The top and bottom 2.5% of page view data are removed to eliminate outliers.

## Testing

- Unit tests are provided in `test_module.py` and run automatically with `main.py`.

## License

This project is part of the freeCodeCamp Data Analysis with Python curriculum.