# sp500-strategies

## How to run

- Get data files from [01-edu](https://assets.01-edu.org/ai-branch/project4/project04-20221031T173034Z-001.zip)
- Unzip data, create "data" folder and put files there
- Install miniconda(or use python venv)
- Create a virtual environment
```bash
conda env create -f environment.yml
```
- Activate the virtual environment
```bash
conda activate sp500
```
- Run Jupyter Notebook
```bash
jupyter notebook
```
- Open browser http://localhost:8888
- Browse to notebook folder and open sp500_strategies.ipynb (all the code is in this notebook)
- Run all cells
- Check results folder
- If you can't run the code, you can also see result in the notebook output cells before running.
