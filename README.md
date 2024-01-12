**[contents](#Contents) | [setup](#Setup) | [running the notebooks](#running-the-notebooks) | [issues](#issues)**

# CPERS
code to process permafrost ERT data from the CPERS database

## Contents

This respository contains a [jupyter notebook](./data_processing_CPERS.ipynb) that contains code to process the data contained in the CPERS database. This data is available in a [Nordicana D data publication](https://nordicana.cen.ulaval.ca/dpage.aspx?doi=45855XD-DC9883ABD609428B)

## Setup

Here are step-by-step instructions for running this notebooks on your machine:

Install Python. You can use [anaconda](https://www.anaconda.com/download/) for this.

Clone this repository by running the following in your command line:

```
git clone https://github.com/teddiherring/CPERS
```

Next, `cd` into the directory you just created:

```
cd CPERS
```

You can use the provided conda environment to set up the necessary software packages:

```
conda env create -f environment.yml
conda activate cpers
```

Next, running the following command

```
jupyter notebook
```

will open a Jupyter notebook in your web browser. You can now open the data processing notebook and start running the code.

## Running the notebook

You can run each cell in the notebook individually by pressing  `shift + enter`, or you can run the entire notebook by selecting `Cell`, `Run All` in the toolbar.

## Issues

Please [make an issue](https://github.com/teddiherring/CPERS/issues) if you encounter any problems while trying to run the notebooks.

