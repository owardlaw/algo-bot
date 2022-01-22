# algo-bot
An algorithmic based machine learning aided crypto trading strategy that allows the user to backtest crypto pairs and create CSV files of historial data from API calls.

# Disclaimer 
Nothing contained in this app should be construed as investment advice.

## Technologies

This project leverages python3 with the following packages:

* [numpy](https://pypi.org/project/numpy/) - For basic math usage.

* [pandas](https://github.com/pandas-dev/pandas) - For organizing data and creating DataFrames.

* [hvplot](https://pypi.org/project/hvplot/) - To gather historical and current market data. 

* [jupyterlab](https://jupyter.org/install.html) - To visualize the code in a modular format. 

* [mathplotlib](https://pypi.org/project/matplotlib/) - For visualizations in python. 

* [sklearn](https://pypi.org/project/scikit-learn/) - A Python module for machine learning built on top of SciPy. 

* [TA-lib](https://pypi.org/project/TA-Lib/) - A Python module for popular technical analysis indicators. 

---

## Installation Guide

Before running the application first install the following.

```python
  pip install jupyterlab
  pip install pandas
  pip install numpy
  pip install hvplot
  pip install jupyterlab
  pip install matplotlib
  pip install scikit-learn
  pip install TA-Lib
```

---

## Usage

* First locate the zip file in the closes folder, unzip it and then the CSV files back into the closes folder. If you wish you generate your own CSV files with the data_scraper it will take awhile.

To use this application first navigate to the closes folder and run the data_scraper.ipynb script. This will generate two large CSV files and this process will take a long time. Once completed navigate back and run the back_testing.ipynb. This will generate plots, and data about the trading period. 

* Note : scikit-learn will generate new predictions everytime the module is ran again. This will change the expected profit of the bot. Random_state can set a            fixed seed for the model to follow and will prevent this. However it restricts scikit-learn to a fixed seed and not doing this can provide a better              understanding of performence given it will be under new circumstances everytime without a fixed seed. 


---

## Contributors

Made by Owen Wardlaw : owardlaw@ucsd.edu.
---

## License

MIT
