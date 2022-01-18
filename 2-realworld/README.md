# Pandas: Datetimes, groupby/value_counts
## 311 analysis
The analysis is based on a subset of a giant dataset, which can be found in [NYC Open Data Website](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9).

The jupyter notebook is [311-analysis.ipynb](https://github.com/AngelineJCQ/pandas-csv-excel-analysis/blob/main/2-realworld/311-analysis.ipynb).

The codes include:
- limit the displayed rows
- change the column name (lowercase and no space)
- fight with .dt (only consider certain month/hour) and .resample (consider both month and year)
- .nlargest() after .groupby
- filter + .resample + plot
- filter certain cells with certain words
- math with datetimes
- pivot table
- some real-world stories (although I didn't finish them all)

## Blossoms analysis
The analysis is based on [KyotoFullFlower7.xls](https://github.com/AngelineJCQ/pandas-csv-excel-analysis/blob/main/2-realworld/KyotoFullFlower7.xls).

The jupyter notebook is [blossoms-analysis.ipynb](https://github.com/AngelineJCQ/pandas-csv-excel-analysis/blob/main/2-realworld/blossoms-analysis.ipynb
The codes include:
- skip first several rows
- add more NaN values
- filter notna rows
- graph rolling average

Note: I used many .strftime('%B') in this notebook, which is dumb and stupid. I will fix it in the next practise. You can check the next folder!
