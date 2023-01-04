Budding_Scholar_22-23
Budding Scholar Project

Data
- Contains gzipped raw data from myDataHelps

Extracted Data
- Contains extraceted dataframe (in csv format) using Daniel's code

selfReport.ipynb
- Uses raw data from myDataHelps to create affect Dataframe

sentiments.ipynb
- Uses affect dataframe generated using selfReport.ipynb
- Creates word and emoji sentiment dataframes using raw data from myDataHelps
- Calculates correlations (using linear mixed regression model) between affects and sentiment metrics

verifyExtractedData
- Code to see differences in output between ExtractedData and rawData
