# datadash
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
The output files will be written in the folder ../output/august_07_2021/..
