# Bachelor End Project — Heuristic vs PPO for Energy Trading

This repository contains the code and data used to compare a rule-based heuristic approach with Proximal Policy Optimization (PPO) for energy trading in a simulated environment.

## 📁 Main File

- The main notebook is [`bep_notebook.ipynb`](bep_notebook.ipynb), which contains all the experiments, models, and analysis.

## ⚙️ Setup Instructions

### 1. Create and Activate Environment

Make sure you have [Anaconda](https://www.anaconda.com/products/distribution) or `miniconda` installed.

```bash
conda create -n bep python=3.10
conda activate bep
pip install -r requirements.txt



### Datasets: 
- prices datasets are in the directory data_prices as .csv files
- consumption dataset, aggregated to 10 minutes intervals can be downloaded from the linkhttps://drive.google.com/file/d/1ZTrZ2X3_XRoN4MfuK3tzh2lkc2y857_w/view?usp=sharing
- battery data is described in the code, it mimics the 
