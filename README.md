# Mod7_SQL

This is a python script that interacts with a SQL database to analyze and plot an ETF..
The script uses "sfo_neighborhoods_census data.csv", "neighborhoods_coordinates.csv", and "housing_per_year.csv" to compile the data
---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For access to Pandas series and dataframes.

* [pathlib](https://github.com/budlight/pathlib) - To load csv files.

* [hvplot.pandas](hvplot.pandas) - To plot data.

* [sqlalchemy](https://docs.sqlalchemy.org/en/14/) - To interact with SQL database.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
import pandas as pd
import hvplot.pandas
from pathlib import Path
import sqlalchemy
```

---

## Usage

To use the etf_analyzer script simply clone the repository and etf_analyzer.ipynb

```python
etf_analyzer.ipynb
```



---

## Contributors

Mike Blanchette

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
