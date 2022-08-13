# Bitcoin
About: Predict BTC price

Files: 
- Bitcoin_data.ipynb: codes to extract bitcoin data from coincap API and save it into csv files
- Bitcoin_compare.ipynb: codes to predict and compare bitcoin prices using fbprophet and ARIMA model
- test.csv: processed test data
- train.csv: processed train data
- README.md: read me file

Summary of process showcased:
- Extract BTC data using coincap API
- Select required data and change to appropriate datatype
- Export and extract data from csv file
- Train and predict next 30 days of data using additive model (Prophet package) and ARIMA model
- Compare actual values with predicted values
