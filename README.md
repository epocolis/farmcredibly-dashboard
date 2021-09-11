# Datadash
Data Dashboard Scripts and code for farmgate, retail and municipal market data in Jamaica

## Requirements: 

Make sure you have the lastest version of pandas installed. see https://pandas.pydata.org/getting_started.html

## How to process the farm_gate files

The python script that processes the farm_gate files is located in the: **datadash/farmgate/farm_analytics** folder.

You can run the script by runing: 
```bash
python agricultural_pricing_analytics.py [-h] input_path output_folder
```

**for example:**

```bash

python agricultural_pricing_analytics.py ../data/raw/farmgate_prices_2020_2021/csv/Farmgate\ 08.07.2021.csv ../output

```
A single output file will be written to ../output/august_07_2021/all_august_07_2021.csv


## How to clean the Urban Municipal  files

The python script that processes the farm_gate files is located in the: **datadash/urban_municipal/urban_municipal_prices_analytics/urban_municipal_data_cleaner** folder.

You can run the script by runing: 
```bash

python urban_municipal_analytics.py  [-h] input_path output_folder
```

**for example:**

```bash

python urban_municipal_analytics.py  ../../data/raw/Urban\ Municipal\ 09.04.2021.csv ../../data/output

```
A single output file will be written to ../data/output/september_04_2021/urban_municipal_market_prices_september_04_2021.csv


