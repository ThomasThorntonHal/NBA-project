# Introduction

Thomas Thornton, Student of School of Computer Science, University College Dublin, Ireland, 2021

This is a data science project for Data Science in Practice module, COMP30780.

Title: The developing playstyle of the NBA.

In this project I analyse various NBA statistics to show the change in playstyle of the NBA.

# Order of operations
Run all prep notebooks then
run all analysis notebooks then
run all results notebooks.

# LINK TO DATASETS
In order to run these notebooks you will need to download at least the raw data.
The processed and raw folders should be placed in the data folder.
Download the zip file from these links and extract in data folder.
Processed file is not necessary to download if you run each notebook in order.

Raw data link: https://drive.google.com/file/d/1QRGkDqbIkXDPWNLHGqQ50WHjsVtZQUe5/view?usp=sharing

An empty 'processed' folder is already in the data folder. If you choose to
download the processed data replace the empty folder with this folder.
Processed data link: https://drive.google.com/file/d/1c6MwwaWqSgR5zBQkfJLFN798uNtAKIqy/view?usp=sharing

## Project Structure
The first significant digit of each notebook denotes which research question it belongs to. e.g. '001_base_NBA_dataset' is a notebook for research question 1.
Notebooks that start with 0 are `prep` notebooks.
Notebooks that are 3 digits long and don't start with 0 are `analysis` notebooks.
Notebooks that are 4 digits long are `results` notebooks.

1. _notebooks_ – the main Jupyter notebooks are broken down in to `analysis`, `output`, `prep` and `results`. `prep` is the first set of notebooks which prepares the raw data. `analysis` produces new datasets with new data that I have calculated which will be used in results. `results` contains notebooks that produce our results and graphs.
2. _data_ – the data files to be used; we will separate data into `raw` and `processed` subfolders.
3. _graphs_ – produced graphs and visualisations will be saved here.
