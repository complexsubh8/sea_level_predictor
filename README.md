# Sea Level Predictor

This project is part of the freeCodeCamp Data Analysis with Python certification.

## Project Overview

This project analyzes historical global sea level data and predicts future sea level rise through the year 2050 using linear regression.

The analysis uses:

* Pandas
* Matplotlib
* SciPy

## Dataset

Dataset file:

```text
epa-sea-level.csv
```

Source:

* US Environmental Protection Agency (EPA)
* CSIRO
* NOAA

The dataset contains global average sea level measurements from 1880 onward.

## Features

### Data Visualization

* Scatter plot of observed sea levels

### Linear Regression

Two prediction models are generated:

1. Trend using all available data (1880-present)
2. Trend using data from 2000-present

Both prediction lines are extended through 2050.

## Installation

```bash
pip install pandas matplotlib scipy numpy
```

## Usage

```bash
python main.py
```

Output:

```text
sea_level_plot.png
```

## Project Structure

```text
sea-level-predictor/
│
├── epa-sea-level.csv
├── sea_level_predictor.py
├── main.py
├── sea_level_plot.png
└── README.md
```

## Author

Subham Sarkar

## Certification

freeCodeCamp - Data Analysis with Python
