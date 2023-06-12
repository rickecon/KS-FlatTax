# Data and code for "How does a Move to a Flat Tax Affect Household Filers? The Case of Kansas"
This repository contains the data and code for the analyses in the *Research in Focus* article by [Richard W. Evans](https://sites.google.com/site/rickecon) (@rickecon) and Patrick Neyland (@patrickneyland) entitled "How does a Move to a Flat Tax Affect Household Filers? The Case of Kansas".

## Files and directories in the repository
This repository contains the following items:
* [`KS_FlatTax.ipynb` Jupyter notebook](KS_FlatTax.ipynb). An executable notebook you can use to replicate all the analyses in the article and creation of output and figures. You can either clone or download this repository and run the `KS_FlatTax.ipynb` notbook on your machine locally. Or you can [open it in Google Colab](https://colab.research.google.com/drive/1phIZ1oJNs-IjRv7Av7uAHIX3T6P6XVQX?usp=sharing) and run the notebook from your browser in which all the software and computation is hosted in the cloud. To run this notebook locally on your machine, do the following steps:
    * Fork and clone (or download) the https://github.com/TheCGO/KS-FlatTax repository
    * In your computer's terminal, navigate to the directory of the `KS-FlatTax` repository on your local machine.
    * Create the conda environment `ks-flattax-dev` by typing the following command: `conda env create -f environment.yml`
    * Activate the `ks-flattax-dev` conda environment by typing the following command: `conda activate ks-flattax-dev`
    * This should allow your notebook to run while this conda environment is activated.
* [`/images/` directory](images/). This folder contains the `.html` files for the dynamic visualizations in the paper and created in the notebook and the corresponding static `.png` image files.
    * [`/images/rain_totbal_50_ks_timeseries_nosubtxt.html`](/images/rain_totbal_50_ks_timeseries_nosubtxt.html). Dynamic data visualization Bokeh `.html` file, no subtext captions, for web publication. Figure 2. Rainy Day fund and total reserves as a percentage of general fund expenditures: 2000-2023.
    * [`/images/rain_totbal_50_ks_timeseries_nosubtxt.png`](/images/rain_totbal_50_ks_timeseries_nosubtxt.png). Static `.png` file, no subtext captions, for web publication. Figure 2. Rainy Day fund and total reserves as a percentage of general fund expenditures: 2000-2023.
    * [`/images/rain_totbal_50_ks_timeseries.html`](/images/rain_totbal_50_ks_timeseries.html). Dynamic data visualization Bokeh `.html` file with subtext captions. Figure 2. Rainy Day fund and total reserves as a percentage of general fund expenditures: 2000-2023.
    * [`/images/rain_totbal_50_ks_timeseries.png`](/images/rain_totbal_50_ks_timeseries.png). Static `.png` file, with subtext captions. Figure 2. Rainy Day fund and total reserves as a percentage of general fund expenditures: 2000-2023.
    * [`/images/rain_totbal_pct_2022_nosubtxt.html`](/images/rain_totbal_pct_2022_nosubtxt.html). Dynamic data visualization Bokeh `.html` file, without subtext captions, for web publication. Figure 3. 2022 Rainy day Fund Balances and Total Fund Balances as Percent of General Fund Expenditures.
    * [`/images/rain_totbal_pct_2022_nosubtxt.png`](/images/rain_totbal_pct_2022_nosubtxt.png). Static `.png` file, without subtext captions, for web publication. Figure 3. 2022 Rainy day Fund Balances and Total Fund Balances as Percent of General Fund Expenditures.
    * [`/images/rain_totbal_pct_2022.html`](/images/rain_totbal_pct_2022.html). Dynamic data visualization Bokeh `.html` file, with subtext captions. Figure 3. 2022 Rainy day Fund Balances and Total Fund Balances as Percent of General Fund Expenditures.
    * [`/images/rain_totbal_pct_2022.png`](/images/rain_totbal_pct_2022.png). Static `.png` file, with subtext captions. Figure 3. 2022 Rainy day Fund Balances and Total Fund Balances as Percent of General Fund Expenditures.
    * [`/images/state_taxtype_2023.html`](/images/state_taxtype_2023.html). Dynamic data visualization Bokeh `.html` file. Figure 1. Type of state employment income tax system as of January 2023.
    * [`/images/state_taxtype_2023.png`](/images/state_taxtype_2023.png). Static `.png` file. Figure 1. Type of state employment income tax system as of January 2023.
* [`/data/` directory](data/). This directory contains the data used in the analyses in the article--PEW total balances and rainy day fund balances historical data for all 50 states.
    * [`/data/cb_2018_us_state_20m`](/data/cb_2018_us_state_20m). Folder containing US Census Bureau shapefiles (7 files) and corresponding files for US states. We use the "<1.0 MB" files (the `_20m` extension). See https://www.census.gov/geographies/mapping-files/2018/geo/carto-boundary-file.html.
    * [`/data/fig2_source.csv`](/data/fig2_source.csv). Source data for Figure 2 in the paper.
    * [`/data/fig3_source.csv`](/data/fig3_source.csv). Source data for Figure 3 in the paper.
    * [`/data/ReservesBalancesData.xlsx`](data/ReservesBalancesData.xlsx). PEW Charitable Trusts historical data on all 50 states total balances and rainy day fund balances from 2000 - 2023. "[Fiscal 50: State Trends and Analysis: Reserves and Balances](https://www.pewtrusts.org/en/research-and-analysis/data-visualizations/2014/fiscal-50#ind5)", updated May 17, 2023 (accessed May 26, 2023). Data can be downloaded from the PEW site from this URL (https://www.pewtrusts.org/-/media/data-visualizations/interactives/2016/fiscal-50/docs/2013/ReservesBalancesData.xlsx?v=20230322).
    * [`/data/state_taxtype.csv`](/data/state_taxtype.csv). Data on 50 states plus District of Columbia state employment income tax type.
