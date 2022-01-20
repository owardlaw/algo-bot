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


To use the application simply clone the repository and open with JupyterLab. Proceed to run the modules and visualize the plotted data, and view the organized data. Change the window of the data calculated in the training section to note different recall and precision factors in the testing report.  

* Note : if you are using an Apple Silicon machine and encounter installation errors, try installation with brew or conda. 

* Note : scikit-learn will generate new predictions everytime the module is ran again. This will change the expected profit of the bot. Random_state can set a            fixed seed for the model to follow and will prevent this. However it restricts scikit-learn to a fixed seed and not doing this can provide a better              understanding of performence given it will be under new circumstances everytime without a fixed seed. 


---

## Contributors

Made by Owen Wardlaw : owardlaw@ucsd.edu.
---

## License

MIT
