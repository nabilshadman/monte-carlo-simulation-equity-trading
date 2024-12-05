# Monte Carlo Simulation in Equity Trading 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Python](https://img.shields.io/badge/python-3.x-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)

## Overview
This project explores the application of [**Monte Carlo**](https://en.wikipedia.org/wiki/Monte_Carlo_method) simulations in equity trading, leveraging statistical distributions to model financial behaviors.

The methodologies implemented include:
- **Geometric Brownian Motion (GBM)**: Simulating equity price paths
- **Pareto Distribution**: Simulating equity trading volumes

<table width="100%">
<tr>
<td width="50%"><strong>Geometric Brownian Motion (GBM)</strong></td>
<td width="50%"><strong>Pareto Distribution</strong></td>
</tr>
<tr>
<td><img src="https://github.com/nabilshadman/monte-carlo-simulation-trading/assets/13073461/330c43b3-b4fa-44ba-9338-aa553b9825fc" width="100%" alt="Simulated equity price paths using GBM"></td>
<td><img src="https://github.com/nabilshadman/monte-carlo-simulation-trading/assets/13073461/6a9cfa5b-3fec-4933-af23-df0b27672be9" width="100%" alt="Simulated equity trading volume using Pareto distribution"></td>
</tr>
<tr>
<td><em>Simulating equity price paths</em></td>
<td><em>Simulating equity trading volumes</em></td>
</tr>
</table>

### Tech Stack
- **Python Libraries**: 
  - scipy
  - numpy
  - pandas
  - matplotlib
- **Development Environment**: Jupyter Notebook
- **Version Control**: GitHub


## Notebooks  

### 1. [**Lognormal Distribution**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/lognormal_distribution.ipynb)  
Provides a Python implementation of the **lognormal distribution**, a key component in modeling financial price movements.  
- Visualizes histogram, Probability Density Function (PDF), and Cumulative Distribution Function (CDF).  
- Foundation for simulating equity prices.  

### 2. [**Pareto Distribution**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/pareto_distribution.ipynb)  
Implements the **Pareto distribution**, often used for modeling trading volumes.  
- Visualizes histogram and PDF.  
- Forms the basis for simulating trading volume.  

### 3. [**Simulating Equity Prices**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/simulating_equity_prices.ipynb)  
Simulates **equity price paths** using the GBM process.  
- Explains the relationship between periodic returns and lognormal price distributions.  
- Uses Python’s NumPy for efficient computation.  

### 4. [**Simulating Trading Volume**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/simulating_trading_volume.ipynb)  
Simulates **trading volumes** with the Pareto distribution.  
- Generates realistic equity volumes lacking autocorrelation and price dependency.  

---

## Environment  

### Recommended Setup  
For seamless execution, use the [**Anaconda Distribution**](https://docs.anaconda.com/free/anaconda/index.html), which simplifies dependency management and ensures compatibility.  

1. Download and install Anaconda from [here](https://www.anaconda.com/download).  
2. Open **Anaconda Navigator** and launch Jupyter Notebook.  
3. Navigate to the project directory to begin.  

---

## Execution  

### Running the Notebooks  
1. Open a notebook in Jupyter.  
2. In the toolbar, select **Run** → **Run All Cells** to execute sequentially.  

### Suggested Order  
For those new to Monte Carlo simulations in finance, follow this order:  
1. [**lognormal_distribution.ipynb**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/lognormal_distribution.ipynb)  
2. [**pareto_distribution.ipynb**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/pareto_distribution.ipynb)  
3. [**simulating_equity_prices.ipynb**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/simulating_equity_prices.ipynb)  
4. [**simulating_trading_volume.ipynb**](https://github.com/nabilshadman/monte-carlo-simulation-equity-trading/blob/main/simulating_trading_volume.ipynb)  

For detailed instructions, refer to the [Jupyter documentation](https://docs.jupyter.org/en/latest/).  

## Contributing

We welcome contributions! Please feel free to submit pull requests or open issues for any improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE.txt) file for details. 

## Citation  

If you use this work in your research, please cite:  

```bibtex
@misc{monte-carlo-equity-trading,
  author = {Shadman, Nabil},
  title = {Monte Carlo Simulation in Equity Trading},
  year = {2023},
  publisher = {GitHub},
  url = {https://github.com/nabilshadman/monte-carlo-simulation-trading}
}
```
