Final Project
Names: Bryce Grover, Jason Kim

Files: 
- FinalProject_Report.pdf
- Finished_OlympicModel.ipynb
- Finished_Predict_BG+JK_100Fr.ipynb
- Finished_Predict_BG+JK_Month.ipynb
- ReadMe.txt

Sources:
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.merge.html
- https://stackoverflow.com/questions/18171739/unicodedecodeerror-when-reading-csv-file-in-pandas
- https://stackoverflow.com/questions/45099352/how-to-convert-format-time-hhmmss-ss-to-hhmmss-ss-in-python
- https://matplotlib.org/stable/plot_types/basic/plot.html#sphx-glr-plot-types-basic-plot-py
- https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html
- https://www.mathworks.com/help/deeplearning/ug/long-short-term-memory-networks.html
- https://stackoverflow.com/questions/49330195/how-to-use-inverse-transform-in-minmaxscaler-for-a-column-in-a-matrix
- CPSC393 classwork
- CPSC392 classwork

Overview:
This project uses LSTM models to forecast future swimming results using Olympic data and personal data of swimmers.

Divison of Labor:
- Bryce:
    - Wrote code for model that forecasts future race results for Olympic Games using hostorical Olympic data. (Finished_OlympicModel.ipynb)
    - Wrote code for model that forecasts future race results for Bryce and Jason using their personal swim career stats. (Finished_Predict_BG+JK_100Fr.ipynb)
    - Created visualizations in the code files and in the report.
    - Wrote the Final Report.
- Jason:
    - Wrote code for model that forecasts in which month Bryce and Jason will have the best swim race performances in a year. (Finished_Predict_BG+JK_Month.ipynb)