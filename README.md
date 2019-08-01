## Creating Customer Segments using Unsupervised Learning Techniques

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [Jupyter Notebook (IPython) 4.10.0](https://ipython.org/)
- [numPy 1.16.4](http://www.numpy.org/)
- [Pandas 0.24.2](http://pandas.pydata.org/)
- [matplotlib 2.2.4](http://matplotlib.org/)
- [scikit-learn 0.17](http://scikit-learn.org/stable/)

### Code

The code is provided in the `market-segmentation.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `customers.csv` dataset file to comile the project your work.

### Run

In a terminal or command window, navigate to the top-level project directory `market-segmentation/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook market-segmentation.ipynb.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

## Data

The customer segments data is included as a selection of 440 data points collected on data found from clients of a wholesale distributor in Lisbon, Portugal. More information can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

Note (m.u.) is shorthand for *monetary units*.

**Features**
1) `Fresh`: annual spending (m.u.) on fresh products (Continuous); 
2) `Milk`: annual spending (m.u.) on milk products (Continuous); 
3) `Grocery`: annual spending (m.u.) on grocery products (Continuous); 
4) `Frozen`: annual spending (m.u.) on frozen products (Continuous);
5) `Detergents_Paper`: annual spending (m.u.) on detergents and paper products (Continuous);
6) `Delicatessen`: annual spending (m.u.) on and delicatessen products (Continuous); 
7) `Channel`: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
8) `Region`: {Lisbon - 1, Oporto - 2, or Other - 3} (Nominal) 
