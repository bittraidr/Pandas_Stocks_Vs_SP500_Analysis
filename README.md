# Challenge 4
## Whale Returns, Algo Returns, and SP500 History
- predominantly used all previous activity assignments to figure out each section
- used this link to help change the date format for SP500 index
     https://stackoverflow.com/questions/51310072/how-to-change-format-of-data-to-ymd-in-pandas
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DatetimeIndex.strftime.html
These in addition for plotting beta 
- https://stackoverflow.com/questions/50149562/jupyterlab-interactive-plot
- https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.beta.html
- https://stackoverflow.com/questions/62758122/how-to-add-an-interactive-plot-in-jupyter-notebook

  Also found this site that helped me with this line of code
- all_stocks_reset_index.index = all_stocks_reset_index.index.to_series().apply(lambda x: x[0])
https://stackoverflow.com/questions/22407798/how-to-reset-a-dataframes-indexes-for-all-groups-in-one-step
