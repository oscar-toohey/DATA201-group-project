# DATA201-group-project
DATA201 - group project

2021_Group_Project.ipynb:
Downloaded handout from the learn page.

Notebook_Final.ipynb:
This notebook is a compilation of the wrangling notebooks so that all of the information is in one place and so that the graphs can be overlayed on each other.

SCRAPING_COVID_CASES.ipynb:
This notebook shows the process of scraping the shipping data from the StatsNZ api.

SCRAPING_SHIPPING.ipynb:
This notebook shows the process of scraping the covid data from the StatsNZ api.

wrangled_CPI.ipynb:
This notebook shows the process of wrangling the consumer price index data so that it is useable in graphs.

wrangled_import_export.ipynb:
This notebook shows the process of wrangling the shipping data so that it is useable in graphs.

wrangled_numcase.ipynb:
This notebook shows the process of wrangling the covid data so that it is useable in graphs.


Household Living Costs CSV:
This dataset we got from StatsNZ. It shows the quarterly CPI for all areas from 2008 to 2021.

Number of Cases CSV:
This dataset was scraped from the StatsNZ api. It shows the daily covid cases in 3 categories; active, recovered and deceased. This dataset ranges from Feb 2020 to Oct 2021.


Overseas Cargo CSV:
This dataset was scraped from the StatsNZ api. It shows the imports and exports of cargo ships in New Zealand from 1988 to 2021.


Wrangled CPI CSV:
This CSV contains the Consumer Price Index data that is relevant to the questions that we have about how covid affected the cost of living in New Zealand

Quarter: This column contains the year and quarter of the data
All Goups: This column contains the average price of all categories in the original dataset
Food: This column contains the price of food by quarter
Petrol: This column contains the price of petrol by quarter
Rent: This column contains the price of rent by quarter


Wrangled Trade CSV:
This CSV contains the shipping data that is relevant to our question on how covid affected the cost of living. We chose these columns because they made the most sense for us to use in comparison

Period: This column contains the day of the row
Trade: This column tells whether the specific row is an import or export
Gross_Weight_kt: This column contains the gross weight of the shipment in kilotonnes
NZD_Value_mil: This column contains the total value of the shipment in millions of dollars
