# stockAnalysis
This project predicts which stocks will outperform.

git clone git@github.com:ravivalluri/stockAnalysis.git

cd stockAnalysis

This project uses python 3.6, and the common data science libraries pandas and scikit-learn.To install all of the requirements at once, run the following code in terminal:

pip install -r requirements.txt

pip install pandas-datareader

pip install fix_yahoo_finance --upgrade --no-cache-dir

Download the csv file from yahoo finance here(https://finance.yahoo.com/quote/%5EGSPC/history?p=%5EGSPC) and place it into the project directory and rename it sp500_index.csv

python download_historical_prices.py

pip install tqdm

python parsing_keystats.py

pip install sklearn

python backtesting.py

python current_data.py

python stock_prediction.py
