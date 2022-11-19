# Lesson Data
This repo contains lessons data used for any lectures or workshops.

# 1 - Environment Prep

## 1.1 - With Internet Access
No environment prep required. You will need a Google account because the lesson data can be used on [Google Colab](https://colab.research.google.com/).
Google Colab is a free service that allows users to access ready-to-use Python development environments.

## 1.2 - Without Internet Access
If the workshop has no access to reliable internet then the environment should be prepared beforehand. For participants without
[Rasterio](https://rasterio.readthedocs.io/en/latest/) or [GDAL](https://gdal.org/) installed on their computer they are advised to do the following:

1. Download the [Anaconda](https://www.anaconda.com/) distribution of Python
2. Run through the standard installation process and ensure Anaconda is added to the system PATH
3. Open your terminal and type this command `conda create -n geo python=3.9`. Type Yes to any questions asked by Anaconda and wait for environment to be created
4. Activate virtual environment by typing `conda activate geo`
5. Install Python packages in virtual environment by typing `conda install -c conda-forge rasterio`
6. Install [VS Code](https://code.visualstudio.com) which can read the Jupyter Notebook files. Here are [additional notes](https://code.visualstudio.com/docs/datascience/jupyter-notebooks) on how to use Jupyter Notebook in VS Code
