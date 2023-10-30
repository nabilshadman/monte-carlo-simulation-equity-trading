# 1. Monte Carlo Simulation in Trading
In this project, we apply **monte carlo** simulation in trading. Particularly, we apply the **Geometric Brownian Motion (GBM)** to simulate equity prices. Also, we use the **Pareto distribution** to simulate equity trading volume.  

**Tech Stack:** Python (scipy, numpy, pandas, matplotlib).  


# 2. Notebooks
In this section, we describe the **notebooks** of the project.  

- **lognormal_distribution.ipynb**  
This notebook contains a Python implementation of the **lognormal distribution**. The lognormal distribution is a continuous probability distribution of a random variable whose logarithm is normally distributed. The notebook provides an overview of the lognormal distribution and its properties. We generate random numbers from the lognormal distribution. Then, we use the samples to visualise the histogram, along with the PDF and the CDF of the distribution. This notebook serves as the base knowledge from which we build our simulation of equity prices.  

- **pareto_distribution.ipynb**  
This notebook contains a Python implementation of the Pareto distribution. The Pareto distribution is a continuous probability distribution of a random variable that has a power-law relationship between its tail and its body. The notebook provides an overview of the Pareto distribution and its properties. We generate random numbers from the Pareto distribution. Then, we use the samples to visualise the histogram, along with the PDF and the CDF of the distribution. This notebook serves as the base knowledge from which we build our simulation of equity trading volume.  

- **simulating_equity_prices.ipynb**  
This notebook contains a Python implementation of simulating equity prices. The notebook provides an overview of the geometric Brownian motion (GBM) process, which is used to model the behavior of equity prices. It then goes on to explain how Monte Carlo simulations can be used to simulate equity prices using GBM. The code implementation uses Python’s NumPy library to simulate equity prices using a Monte Carlo simulation. The results of the simulation are plotted using Matplotlib.  

- **simulating_trading_volume.ipynb**  
This notebook contains a Python implementation of simulating equity trading volume. The notebook provides an overview of how to simulate equity trading volume using the Pareto distribution. Using a Pareto distribution, the simulation generates integer trading volumes for equities. The generated data, resembling typical large-cap equity volumes, lacks correlation with asset prices and does not exhibit autocorrelation.  

# 3. Environment
We recommend installing **Anaconda Distribution** before running the notebooks as Anaconda provides a powerful package management system called Conda, which can handle complex software environments and ensures compatibility between different packages. Conda simplifies the setup process and avoids version conflicts.  

- Download Anaconda Distribution from this [page](https://www.anaconda.com/download) and run the installer.  

- Once installation is finished, launch Anaconda Navigator, which provides a graphical user interface to manage your Anaconda environment.  

- In Anaconda Navigator, you should see a button labeled "Launch" under the Jupyter Notebook section. Click on it to start Jupyter Notebook in your default web browser.
  
- Navigate to the directory of this project on your system. 


# 4. Execution  
In this section, we describe the steps to **run** the notebooks. As there are no dependencies between the notebooks, one can run one or several of the notebooks in any order. For a beginner interested in Monte Carlo simulation, we recommend the order below. This will ensure one has the sufficient proability background before understanding how we applied the probability concepts in our simulations.  

- Run **lognormal_distribution.ipynb**
  
- Run **pareto_distribution.ipynb**
  
- Run **simulating_equity_prices.ipynb**

- Run **simulating_trading_volume.ipynb**  

