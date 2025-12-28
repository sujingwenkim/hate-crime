# Uncovering Patterns of Hate: An Exploratory Analysis of U.S. Hate Crime Data (1991–2023)
##### Author: Sujin Kim

This project analyzes long-term trends in hate crimes across the United States using publicly available data from the FBI Crime Data Explorer. It was developed as part of a graduate course assignment on data exploration at Johns Hopkins University.

## Files

- `index.qmd`: Quarto source file with all code and analysis
- `index.html`: Rendered output (HTML report)
- `hate_crime.rds`: Compressed dataset converted from the original FBI CSV
- `README.md`: Project overview and instructions on reproduction

## How to Reproduce

1. Clone or download this repository
2. Open `index.qmd` in RStudio
3. Ensure the following packages are installed: `tidyverse`, `lubridate`, `ggplot2`, `knitr`
4. Load the dataset using:
```r
crime <- readRDS("hate_crime.rds")
```
5. Run all code chunks, or render the document by clicking **Render** in RStudio or using:
```r
quarto::quarto_render("index.qmd")
```

## Data Source

Federal Bureau of Investigation. (2024, September 23). _Crime Data Explorer: Hate Crime Statistics_ [Data file]. U.S. Department of Justice. https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/downloads#datasets

_Note: Due to GitHub file size restrictions, the original CSV file has been converted and compressed to RDS format for efficient replication._



