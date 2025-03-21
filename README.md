# Snippington Python Pandas Basic
Visual Studio Code extension for Pandas code snippets.

This works with __ipynb__ (Jupyter Notebook) files in Visual Studio Code too.

> Notice: Starting from version **0.1.8**, AI and GPT platforms will be used to generate new shortcuts and snippets.

### Data Exploratory Shortcuts

| Prefix | Description |
| ------ | ------------ |
| `pd: imp` | Import Pandas |
| `pd: read-csv` | Read CSV File |
| `pd: read-csv-chunked` | Read CSV File in Chunks |
| `pd: read-csv-skiprows` | Read CSV with skipping rows |
| `pd: stats` | Show aggregate stats. |
| `pd: stats-custom` | Get Custom Aggregate Stats |
| `pd: shape` | Get the shape of dataframe |
| `pd: row-count` | Get the row count of dataframe |
| `pd: column-count` | Get the column count of dataframe |
| `pd: first-x-rows` | Get the first x rows of dataframe |
| `pd: last-x-rows` | Get the last x rows of dataframe |
| `pd: n-largest` | Get the n largest values of a column in a dataframe. |
| `pd: n-smallest` | Get the n smallest values of a column in a dataframe. |
| `pd: set-categories` | Define categories |
| `pd: frequency-distribution` | Get frequency distribution of values for a column |
| `pd: data-sample` | Get sample of data from dataframe |
| `pd: column-select` | Select single column from dataframe |
| `pd: column-select-multiple` | Select multiple columns from dataframe |
| `pd: rows-specific-columns` | Select rows by indices for specific column names in dataframe |
| `pd: rows-by-index` | Select rows from dataframe by indices |
| `pd: columns-by-index` | Select columns from dataframe by indices |
| `pd: group-by-count` | Group By with Count Aggregate |
| `pd: group-by-mean` | Group By with Mean |
| `pd: window-expanding-mean` | Expanding Window Mean |
| `pd: window-rolling-mean` | Expanding Window Mean |

### Data Manipulation Shortcuts

| Prefix | Description |
| ------ | ------------ |
| `pd: dataframe-create` | Create custom dataframe |
| `pd: columns-rename` | Assign new column names to dataframe |
| `pd: columns-rename-specific` | Assign new column names to specific columns in dataframe |
| `pd: replace` | Replace values a dataframe. |
| `pd: columns-drop` | Drop columns by name |
| `pd: duplicates-drop` | Drop duplicate columns by name |
| `pd: sort-by-column` | Sort values in dataframe by column |
| `pd: filter` | Filter dataframe based on condition/match |
| `pd: filter-by-query` | Filter dataframe by query based on conditions|
| `pd: apply-all` | Apply function to all of dataframe |
| `pd: apply-single-column` | Apply function to a specific column |
| `pd: apply-multiple-columns` | Apply function to multiple columns |
| `pd: apply-column-lambda` | Apply lambda function to column |
| `pd: convert-numeric` | Convert all columns to numeric type |
| `pd: convert-column-numeric` | Convert a single column to numeric type |
| `pd: convert-columns-numeric` | Convert multiple columns to numeric type |
| `pd: set-data-types` | Assign data types to columns |
| `pd: dataframes-concatenate` | Concatenate dataframes |
| `pd: pivot-table` | Create Pivot table |

### Time Series Operations Shortcuts

| Prefix | Description |
| ------ | ------------ |
| `pd: parse-dates` | Read CSV with date parsing |
| `pd: resample` | Resample time series data to a different frequency |
| `pd: date-range` | Create a date range with pandas |
| `pd: filter-date-range` | Filter dataframe by date range |
| `pd: date-components` | Extract date components from datetime column |
| `pd: time-shift` | Shift time series data by periods |
| `pd: time-lag-features` | Create multiple lag features for time series analysis |
| `pd: time-diff` | Calculate differences between consecutive periods |
| `pd: time-pct-change` | Calculate percentage change between consecutive periods |
| `pd: set-datetime-index` | Set a datetime column as index and sort |

### Missing Data Fix Shortcuts

| Prefix | Description |
| ------ | ------------ |
| `pd: fill-mean` | Fill missing values with mean values |
| `pd: fill-median` | Fill missing values with median values |
| `pd: fill-mode` | Fill missing values with modal values |

### Output Shortcuts

| Prefix | Description |
| ------ | ------------ |
| `pd: write-to-excel` | Write dataframe to Excel file |
| `pd: write-to-csv` | Write dataframe to CSV file |

### Plotting Shortcuts

| Prefix | Description |
| ------ | ------------ |
| `pd: scatter-plot` | Create a scatter Plot |
| `pd: bar-plot` | Create a bar plot |
| `pd: line-plot-multiple` | Create a multiple line plot |
| `pd: plot-save` | Save plot to output file |
| `pd: bar-plot-horizontal` | Horizontal bar plot |
| `pd: histogram` | Make a histogram |
| `pd: histogram-columns` | Make a histogram for each column |

### Pre-reqs 

Make sure you have Python, Pandas and Matplotlib installed (optional: for plots only).

```bash
pip3 install pandas
pip3 install matplotlib
```