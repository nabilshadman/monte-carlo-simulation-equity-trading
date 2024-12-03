# Monte Carlo Simulation in Equity Trading  
In this study, we apply [**Monte Carlo**](https://en.wikipedia.org/wiki/Monte_Carlo_method) simulation in equity trading. Particularly,  

[1] We apply the [**Geometric Brownian Motion (GBM)**](https://en.wikipedia.org/wiki/Geometric_Brownian_motion) to simulate equity prices (Figure 1).  
![gbm](https://github.com/nabilshadman/monte-carlo-simulation-trading/assets/13073461/330c43b3-b4fa-44ba-9338-aa553b9825fc)  
**Figure 1:**  Simulated equity price paths using GBM.  

[2] Also, we use the [**Pareto distribution**](https://en.wikipedia.org/wiki/Pareto_distribution) to simulate equity trading volume (Figure 2).  
![paretovol](https://github.com/nabilshadman/monte-carlo-simulation-trading/assets/13073461/6a9cfa5b-3fec-4933-af23-df0b27672be9)  
**Figure 2:** Simulated equity trading volume using Pareto distribution.   

**Tech Stack:** Python (scipy, numpy, pandas, matplotlib, jupyter), GitHub.


## Notebooks
In this section, we describe the **notebooks** of the project.  

- [**lognormal_distribution.ipynb**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/lognormal_distribution.ipynb)
  This notebook contains a Python implementation of the **lognormal distribution**. The lognormal distribution is a continuous probability distribution of a random variable whose logarithm is normally distributed. The notebook provides an overview of the lognormal distribution and its properties. We generate random numbers from the lognormal distribution. Then, we use the samples to visualise the histogram, along with the PDF (and the CDF) of the distribution. This notebook serves as the base knowledge from which we build our simulation of equity prices.  

- [**pareto_distribution.ipynb**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/pareto_distribution.ipynb)
  This notebook contains a Python implementation of the **Pareto distribution**. The Pareto distribution is a continuous probability distribution of a random variable that has a power-law relationship between its tail and its body. The notebook provides an overview of the Pareto distribution and its properties. We generate random numbers from the Pareto distribution. Then, we use the samples to visualise the histogram, along with the PDF of the distribution. This notebook serves as the base knowledge from which we build our simulation of equity trading volume.  

- [**simulating_equity_prices.ipynb**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/simulating_equity_prices.ipynb)
  This notebook contains a Python implementation of simulating **equity prices**. The notebook provides an overview of the GBM process. It then goes on to explain how Monte Carlo simulations can be used to simulate equity prices using GBM. Although the periodic returns in GBM follow a normal distribution, the resulting multi-period price levels, such as those spanning ten days, exhibit a lognormal distribution. The code implementation uses Python’s NumPy library to simulate equity prices. The results of the simulation are plotted using Matplotlib.  

- [**simulating_trading_volume.ipynb**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/simulating_trading_volume.ipynb)
  This notebook contains a Python implementation of simulating **equity trading volume**. The notebook provides an overview of how to simulate equity trading volume using the Pareto distribution. Using a Pareto distribution, the simulation generates integer trading volumes for equities. The generated data, resembling typical large-cap equity volumes, lacks correlation with asset prices and does not exhibit autocorrelation.  

## Environment
We recommend installing [**Anaconda Distribution**](https://docs.anaconda.com/free/anaconda/index.html) before running the [Jupyter](https://jupyter.org/) notebooks as Anaconda provides a powerful package management system called Conda, which can handle complex software environments and ensures compatibility between different packages. Conda simplifies the setup process and avoids version conflicts.   

- Download Anaconda Distribution from this [page](https://www.anaconda.com/download) and run the installer.  
- Once installation is finished, launch Anaconda Navigator, which provides a graphical user interface to manage your Anaconda environment.  
- In Anaconda Navigator, you should see a button labeled "Launch" under the Jupyter Notebook section. Click on it to start Jupyter Notebook in your default web browser.
- Navigate to the directory of this project on your system. 


## Execution  
In this section, we describe the steps to **run** the notebooks. To run any notebook, open the notebook first. Then, in the toolbar of the notebook, click on the option **Run** and then select **Run All Cells** from the dropdown menu. The notebook will start executing each cell sequentially from top to bottom.  

As there are no dependencies between the notebooks, one can run one or several of the notebooks in any order. For a beginner interested in Monte Carlo simulation in finance, we **recommend** the order below. This will ensure one has the sufficient proability background before looking at how we applied the probability concepts in our simulations.  


- Run [**lognormal_distribution.ipynb**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/lognormal_distribution.ipynb)
- Run [**pareto_distribution.ipynb**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/pareto_distribution.ipynb)
- Run [**simulating_equity_prices.ipynb**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/simulating_equity_prices.ipynb)
- Run [**simulating_trading_volume.ipynb**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/simulating_trading_volume.ipynb)

For more info on Jupyter Notebook, check out the [documentation](https://docs.jupyter.org/en/latest/).  
