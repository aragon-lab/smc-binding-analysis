
[![DOI](https://zenodo.org/badge/948591691.svg)](https://doi.org/10.5281/zenodo.15050842)

# Scripts for SMC binding analysis
Scripts used in the publication "Visualising binding of single SMC complexes to DNA substrates using combinational optical tweezers and fluorescence microscopy".

## Downloading scripts
The easiest way to download the scripts in this repository is by clicking the green "Code" button above and selecting "Download ZIP".  This will give access to the latest version of each notebook.

## Installation using Anaconda
The environment.yml files in this repository contain a list of the Python packages needed to run the notebooks.  These can be used to create a new Anaconda environment, which acts as a self-contained copy of Python that has all the relevant packages installed.  This environment can be created either using the Anaconda Navigator graphical interface or from Powershell.  There are two environment.yml files, one for Mac and one for Windows.


### Installation using Anaconda's graphical interface 
1. Install [Anaconda](https://www.anaconda.com/download/success)
2. Start installed copy of "Anaconda Navigator"
3. Inside Anaconda Navigator, click the "Environments" button on the left, then "Import" at the bottom of the list of existing environments.  Note: initially there will only be one called "root (base)".
4. In the "Import new environment" window that opens, enter the environment name as "smc-binding-analysis" and select the relevant "environment.yml" file that you downloaded from this repository

### Installation from Powershell
1. Install [Anaconda](https://www.anaconda.com/download/success)
2. Start installed copy of "Anaconda Powershell Prompt"
3. Use the following command to create the environment:
    
    - `conda env create -f [path to environment.yml]`


## Running notebooks
As with installation, Jupyter can be started either via the graphical Anaconda Navigator or from Powershell.  For this simple operation, the Powershell route is usually signficantly faster.

#### From the graphical interface
1. Start installed copy of "Anaconda Navigator"
2. Inside Anaconda Navigator, click the "Environments" button on the left, then click the play button next to "smc-binding-analysis" in the environment list and select "Open with Jupyter Notebook".

#### From Powershell
1. Start installed copy of "Anaconda Powershell Prompt"
2. Use the following command to activate the *smc-binding-analysis* environment

    `conda activate smc-binding-analysis`

3. Start JupyterLab with the following command

    `jupyter lab`

## Running test images
Each script is configured to run a provided test image, which is stored in the "test_folder" directory.  Due to the size of these files (~700 MB in total), these need to first be downloaded from [Zenodo](https://zenodo.org/records/15028071).