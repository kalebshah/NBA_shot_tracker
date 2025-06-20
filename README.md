# NBA_shot_tracker

This RShiny project explores and visualizes NBA shot data using R. It processes raw shot location data, applies data wrangling techniques, and generates a variety of visual summaries to show player and team shooting patterns.

## Project Structure

- `nba_shots_final.Rmd`: R Markdown report that walks through the entire workflow including data loading, cleaning, analysis, and visualization.
- `data/`: Directory for storing input data files (e.g. raw NBA shot logs).
- `output/`: Directory for saving processed datasets, plots, and tables (if applicable).
- `README.md`: Project overview and usage instructions.

## Features

- 🧹 **Data Cleaning**: Loads and prepares NBA shot data for analysis.
- 📊 **Visualization**: Creates heatmaps, shot charts, and faceted plots for player comparisons.
- 📈 **Statistical Summaries**: Includes summary statistics like shot accuracy, shot zones, and player performance metrics.
- 🧠 **Insights**: Uses descriptive statistics and visual storytelling to uncover key trends in shooting behavior.

## Requirements

This project uses the following R packages:

- `tidyverse` (data manipulation & plotting)
- `ggplot2` (for plotting shot charts)
- `dplyr`, `tidyr` (for wrangling)
- `lubridate` (for working with date/time data)
- `knitr`, `rmarkdown` (for rendering reports)

You can install required packages using:

```r
install.packages(c(
  "tidyverse", "ggplot2", "dplyr", "tidyr", 
  "lubridate", "knitr", "rmarkdown"
))
```

## Running the Analysis
	1.	Open nba_shots_final.Rmd in RStudio.
	2.	Click the Knit button to render the report to HTML or PDF.
	3.	Explore the interactive and visual outputs in the resulting document.

## License

This project is open for educational and non-commercial use. Feel free to fork and adapt the code for your own sports analytics work.