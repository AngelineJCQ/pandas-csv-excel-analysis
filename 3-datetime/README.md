# Pandas: More Datetimes
##  Permit analysis
The analysis is based on a dataset from Pensylvania's Department of Environmental Protection and the file I use is [Permits_Issued_Detail.csv](https://github.com/AngelineJCQ/pandas-csv-excel-analysis/blob/main/3-datetime/Permits_Issued_Detail.csv).

The jupyter notebook is [permit-analysis.ipynb](https://github.com/AngelineJCQ/pandas-csv-excel-analysis/blob/main/3-datetime/permit-analysis.ipynb).

The codes include:
- use .to_datetime to change the data type more wisely
- use ax.set_xticks to change the axis labeling
- graph permits issued by week (W), month (M) and quarter (Q)
- play with .unstack()