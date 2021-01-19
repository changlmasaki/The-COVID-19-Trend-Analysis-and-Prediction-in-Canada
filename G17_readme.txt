README for G17
--------------

G17_extra_graphs (folder) 			<--------- shows extra results more in detail
G17_csv_data_links.txt 				<--------- links to download the csv files to use in the notebook
G17_code_and_data.txt				<--------- link to public google colab
G17_presentation.mp4				<--------- video presentation
G17_Public_Copy_of_COMP_432_Project.ipynb 	<--------- notebook from google colab downloaded locally
G17_readme.txt 					<--------- readme for instructions
G17_report.pdf					<--------- latex report and findings

Our project relies mainly on sklearn, pmdarima, and Prophet.
Our code submission can be found on google collab at:
https://colab.research.google.com/drive/13dn-gJuSn7bq-9iR9t3PEhVhv7QiPOYe?usp=sharing

* The google colab notebook can be ran sequentially as is
* GPU is not required.
* Training only takes a few minutes at most.
* The notebook will save the files locally on the google colab and output are shown directly in the notebook

Data was taken from:
https://www.kaggle.com/mabusalah/brentoilprices
https://github.com/ishaberry/Covid19Canada/tree/master/timeseries_canada

Data can also be downloaded with:
cases_timeseries_canada_csv = wget.download('https://raw.githubusercontent.com/ishaberry/Covid19Canada/master/timeseries_canada/cases_timeseries_canada.csv')
mortality_timeseries_canada_csv = wget.download('https://raw.githubusercontent.com/ishaberry/Covid19Canada/master/timeseries_canada/mortality_timeseries_canada.csv')
recovered_timeseries_canada_csv = wget.download('https://raw.githubusercontent.com/ishaberry/Covid19Canada/master/timeseries_canada/recovered_timeseries_canada.csv')
TemperatureOct2020_csv= wget.download('https://raw.githubusercontent.com/changlmasaki/temp_wind_oct_2020/main/TemperatureOct2020.csv')

For preprocessing and training we relied heavily on the tutorial found at:
https://medium.com/@josemarcialportilla/using-python-and-auto-arima-to-forecast-seasonal-time-series-90877adff03c
https://www.kaggle.com/mabusalah/brentoilprices

Complete source can be found in the report
 