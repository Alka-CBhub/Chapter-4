#  Chapter 4 Phase space reconstruction using PyTISEAN

This repository contains code, and plots for phase space reconstruction using Takens' Theorem for the following models shown below.

## 📚 Models Included

- **1. FitzHugh–Nagumo Model**
- **2. Goodwin Model**
- **3. Mass-Action Model**
- **4. Oregonator Model**
- **5. Glycolytic Oscillations in Yeast**



Each model includes:
- Time-series simulation and selecting a scalar time series
- 2D/3D phase-space visualization for original and reconstructed system
- Latent feature analysis using Singular Value Decomposition

---

## 📁 Folder Structure

<pre> <code> 
├── 1_Fitzhugh_Nagumo_Model_chapter4.ipynb 
├── 2_Goodwin_Model_chapter4.ipynb 
├── ... 
├── Plots_1/ to Plots_5/ 
├── plot_utils.py 

├── environment.yml: Conda environment for reproducibility
├── README.md # This file
</code> </pre>



---

## 🧪 Environment Setup

To reproduce the results or run the notebooks:

Make sure [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or Anaconda is installed.

Then open Git CMD or Anaconda Prompt and run:

```bash
conda env create -f environment.yml
conda activate tiseanpy

This will create and activate the environment with all required packages.

---

## 🚀 Running the Code
After activating the environment, launch Jupyter:
```bash
jupyter notebook
```
Then open and run any of the notebooks in the repository.

---

## 📦 Dependencies
This project uses Python 3.9 with the following key packages:

- `numpy` 
- `scipy` 
- `matplotlib` 
- `jupyter`, `ipykernel` 
- `psutil` 
- `pytisean` – Python wrapper for TISEAN: time-series analysis (embedding, delay plots, etc.)

All dependencies are listed in `environment.yml`.

---
## 📬 Contact
For questions or suggestions, please open an issue on the GitHub repository:  
👉 [https://github.com/Alka-CBhub/Chapter4_PyTISEAN](https://github.com/Alka-CBhub/Chapter4_PyTISEAN)

---