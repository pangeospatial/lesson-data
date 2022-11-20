# Lesson Data
This repo contains lessons data used for any lectures or workshops.

# 1 - Environment Prep

## 1.1 - With Internet Access
No environment prep required. You will need a Google account because the lesson data can be used on [Google Colab](https://colab.research.google.com/).
Google Colab is a free service that allows users to access ready-to-use Python development environments.

## 1.2 - Without Internet Access
If the workshop has no access to reliable internet then the environment should be prepared beforehand. **Please note that these instructions have only been tested on Windows 10.** For participants without
[Rasterio](https://rasterio.readthedocs.io/en/latest/) or [GDAL](https://gdal.org/) installed on their computer they are advised to do the following:

1. Download the [Anaconda](https://www.anaconda.com/) distribution of Python
2. Run through the standard installation process and ensure Anaconda is added to the system PATH


![Anaconda Setup](/docs/anaconda-installation.png "Anaconda Setup")


3. Open your terminal and type this command `conda create -n geo python=3.9 --yes`. Wait for environment to be created.
4. Activate virtual environment by typing `conda activate geo`. There should be the name of your environment in the terminal once it is activated.

![Activate virtual environment](/docs/activate-env.png "Activating virtual environment")


5. Install packages from the conda-forge channel by typing `conda install -c conda-forge rasterio matplotlib --yes`
6. Install packages from the anaconda channel by typing `conda install -c anaconda ipykernel scikit-image scikit-learn --yes`
7. Install [VS Code](https://code.visualstudio.com) which can read the Jupyter Notebook files. Here are [additional notes](https://code.visualstudio.com/docs/datascience/jupyter-notebooks) on how to use Jupyter Notebook in VS Code
8. Open VS Code then click `File` then `Open File` then open the `Radiometric_Correction_and_Image_Preprocessing.ipynb` file.
9. Activate the `geo` environment in the Jupyter Notebook

![Activate jupyter env](/docs/open-jupyter.png "Activate Jupyter Notebook environment")