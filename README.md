# health-data-analysis
# Apple Health Data Extractor, Data Analysis,

This project can help you convert your Apple Health data into CSV files! The code has been broken down into separate scripts to handle the process step-by-step. 



### Extracting and Processing Your Apple Health XML into CSVs and some simple data analysis

- Step 1: Export Apple Health data from the Health on iOS
- Step 2: Download to your computer and decompress the file and place in the apple_health directory instead of qs_ledger. It should look something like your-path-here/qs_ledger/apple_health_export/export.xml
- Step 3: Open up and run the jupyter notebook **apple_health_extractor.ipynb**. This script will parse your XML file and convert it into a series of CSV files. It essentially walks you through a process that runs the python script apple-health-data-parser.py which you can alternatively run directly in terminal or command line. 
- Step 4 (optional):  Open up and run the jupyter notebook **apple_health_data_processor.ipynb** for some additional data processing and simple data analysis using pandas and matplotlib. 

currently working on visualizing dashboard for this health data.
