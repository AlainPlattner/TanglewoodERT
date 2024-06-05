# TanglewoodERT

Requires pyGIMLi, pyBERT, numpy, matplotlib, cmcrameri (colormaps), and jupyter lab or jupyter notebook

## Installation of prerequisites

Install anaconda or minconda from https://www.anaconda.com/ or https://docs.anaconda.com/free/miniconda/

Then in the anaconda prompt, install pyGIMLi through the command
`conda create -n pg -c gimli -c conda-forge "pygimli>=1.5.0" `

To activate pygimli, run
`conda activate pg`

Then install pyBERT
`conda config --add channels gimli --add channels conda-forge`
`conda install -f pybert`

Then install jupyter lab:
`conda install -c conda-forge jupyterlab`

Then the colormaps:
`conda install -c conda-forge cmcrameri`

## Running the software

Open an anaconda prompt and activate pyGIMLi:
`conda activate pg`

Then open jupyter lab
`jupyter lab`

and navigate to the directory where you have the notebooks and data.

Open the `invert.ipynb` notebook to run the installations and the `plotResults.ipynb` to recreate the paper figure.

**Please note that the inversion can take quite a while because the mesh is very fine. You can change the mesh parameters to run a faster inversion.**