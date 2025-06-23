# Good Presentation and Data Visualization Workshop

Theresa Cordero, Raphael Dussin, and Chongxing Fan

June 24, 2025

## Usage

### Install Conda

You can install [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/install#quickstart-install-instructions) or [Miniforge](https://github.com/conda-forge/miniforge).

For advanced users, a Python installation with `pip` and `venv` modules is sufficient.

### Clone this Repo

```shell
git clone https://github.com/cxfan1997/plotting_tutorial
cd plotting_tutorial
```

### Install Packages and Activate Environment

Using conda (you can preview `environment.yml` to see what is inside):

```shell
conda env create -f environment.yml
conda activate plotting_tutorial
```

Using pip (for advanced users):

```shell
python3 -m venv python_env
source python_env/bin/activate
pip install -r requirements.txt
```

### Run Jupyter Notebooks

You can start a Jupyter notebook session by running the command in this directory:

```shell
jupyter notebook
```

Open the notebooks and explore!

- `LinePlots.ipynb`: Prepared by Raphael Dussin
- `Maps.ipynb`: Prepared by Raphael Dussin
- `AdvancedPlot.ipynb`: Prepared by Chongxing Fan

### Remove Environment

After the tutorial, you may want to remove this environment and create your own with only the packages you need.

For conda users:

```shell
conda deactivate
conda env remove -n plotting_tutorial
```

For pip users:

```shell
deactivate
rm -r python_env
```
