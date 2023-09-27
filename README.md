# Data and code for "How does a Move to a Flat Tax Affect Household Filers? The Case of Kansas"
This repository contains the data and code for the analyses in the *Research in Focus* article by [Richard W. Evans](https://sites.google.com/site/rickecon) ([@rickecon](https://github.com/rickecon)) and Patrick Neyland ([@taxpat](https://github.com/taxpat)) entitled "How does a Move to a Flat Tax Affect Household Filers? The Case of Kansas".

## How to run the Jupyter Notebook on your machine
This repository contains a Jupyter Notebook [`KS_FlatTax.ipynb`](KS_FlatTax.ipynb) that can be run locally on your own machine to replicate the analyses in the paper. You can also modify this notebook to use for other analyses you might want to experiment with. To run this notebook locally on your machine, do the following steps:
* Fork and clone (or download) the https://github.com/TheCGO/KS-FlatTax repository
* In your computer's terminal, navigate to the directory of the `KS-FlatTax` repository on your local machine.
* Create the conda environment `ks-flattax-dev` by typing the following command: `conda env create -f environment.yml`
* Activate the `ks-flattax-dev` conda environment by typing the following command: `conda activate ks-flattax-dev`
* This should allow your notebook to run while this conda environment is activated.


## Files and directories in the repository
This repository contains the following items:
* [`KS_FlatTax.ipynb` Jupyter notebook](KS_FlatTax.ipynb). An executable notebook you can use to replicate all the analyses in the article and creation of output and figures.
* [`/images/` directory](images/). This folder contains the `.html` files for the dynamic visualizations in the paper and created in the notebook and the corresponding static `.png` image files.
    * [`/images/CurrReformExtraExempt.html`](/images/CurrReformExtraExempt.html). Dynamic data visualization Bokeh `.html` file, for web publication. Figure 5. Proposed Extra Income Exemption in SB 169 in Addition to Current Kansas Standard Deduction by Filer Type.
    * [`/images/CurrReformExtraExempt.png`](/images/CurrReformExtraExempt.png). Static `.png` file, for web publication. Figure 5. Proposed Extra Income Exemption in SB 169 in Addition to Current Kansas Standard Deduction by Filer Type.
    * [`/images/CurrReformTaxRates.html`](/images/CurrReformTaxRates.html). Dynamic data visualization Bokeh `.html` file, for web publication. Figure 4. Kansas Current Progressive Marginal Tax Rates on Employment Income versus Proposed 5.15 Percent Flat Tax.
    * [`/images/CurrReformTaxRates.png`](/images/CurrReformTaxRates.png). Static `.png` file, for web publication. Figure 4. Kansas Current Progressive Marginal Tax Rates on Employment Income versus Proposed 5.15 Percent Flat Tax.
    * [`/images/NetStateTaxLiabChg_alt1.html`](/images/NetStateTaxLiabChg_alt1.html). Dynamic data visualization Bokeh `.html` file, for web publication. Figure 7. Alternative Policy 1, Dollar Change from Kansas Flat Tax Reform in Filer Net State Income Tax Liability, Flat tax 5.15%, Extra Exempt. $6.15k, $12.3k, $6.15k, $8k.
    * [`/images/NetStateTaxLiabChg_alt1.png`](/images/NetStateTaxLiabChg_alt1.png). Static `.png` file, for web publication. Figure 7. Alternative Policy 1, Dollar Change from Kansas Flat Tax Reform in Filer Net State Income Tax Liability, Flat tax 5.15%, Extra Exempt. $6.15k, $12.3k, $6.15k, $8k.
    * [`/images/NetStateTaxLiabChg_alt2.html`](/images/NetStateTaxLiabChg_alt2.html). Dynamic data visualization Bokeh `.html` file, for web publication. Figure 8. Alternative Policy 2, Dollar Change from Kansas Flat Tax Reform in Filer Net State Income Tax Liability, Flat tax 5.05%, Extra Exempt. $5.85k, $11.7k, $5.85k, $7.5k.
    * [`/images/NetStateTaxLiabChg_alt2.png`](/images/NetStateTaxLiabChg_alt2.png). Static `.png` file, for web publication. Figure 8. Alternative Policy 2, Dollar Change from Kansas Flat Tax Reform in Filer Net State Income Tax Liability, Flat tax 5.05%, Extra Exempt. $5.85k, $11.7k, $5.85k, $7.5k.
    * [`/images/NetStateTaxLiabChg_alt3.html`](/images/NetStateTaxLiabChg_alt3.html). Dynamic data visualization Bokeh `.html` file, for web publication. Figure 9. Alternative Policy 3, Dollar Change from Kansas Flat Tax Reform in Filer Net State Income Tax Liability, Flat tax 5.25%, Extra Exempt. $6.15k, $12.3k, $6.15k, $8k.
    * [`/images/NetStateTaxLiabChg_alt3.png`](/images/NetStateTaxLiabChg_alt3.png). Static `.png` file, for web publication. Figure 9. Alternative Policy 3, Dollar Change from Kansas Flat Tax Reform in Filer Net State Income Tax Liability, Flat tax 5.25%, Extra Exempt. $6.15k, $12.3k, $6.15k, $8k.
    * [`/images/NetStateTaxLiabChg.html`](/images/NetStateTaxLiabChg.html). Dynamic data visualization Bokeh `.html` file, for web publication. Figure 6. Dollar Change from Kansas Flat Tax Reform in Filer Net State Income Tax Liability.
    * [`/images/NetStateTaxLiabChg.png`](/images/NetStateTaxLiabChg.png). Static `.png` file, for web publication. Figure 6. Dollar Change from Kansas Flat Tax Reform in Filer Net State Income Tax Liability.
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
    * [`/data/cb_2018_us_state_20m`](/data/cb_2018_us_state_20m). Folder containing US Census Bureau shapefiles (7 files) and corresponding files for US states. We use the "<1.0 MB" files (the `_20m` extension). See https://www.census.gov/geographies/mapping-files/2018/geo/carto-boundary-file.html. These are used in the creation of the [`/images/state_taxtype_2023.html`](/images/state_taxtype_2023.html) map image in [`KS_FlatTax.ipynb` Jupyter notebook](KS_FlatTax.ipynb).
    * [`/data/CostEstimateWorksheet.xlsx`](/data/CostEstimateWorksheet.xlsx). Excel spreadsheet for estimating the total cost and component cost of different polices. Used in Tables 4 and 5 and in Appendix A.
    * [`/data/fig2_source.csv`](/data/fig2_source.csv). Source data for Figure 2 in the paper.
    * [`/data/fig3_source.csv`](/data/fig3_source.csv). Source data for Figure 3 in the paper.
    * [`/data/fig6_source.csv`](/data/fig6_source.csv). Source data for Figure 6 in the paper.
    * [`/data/fig7_source.csv`](/data/fig7_source.csv). Source data for Figure 7 in the paper.
    * [`/data/fig8_source.csv`](/data/fig8_source.csv). Source data for Figure 8 in the paper.
    * [`/data/fig9_source.csv`](/data/fig9_source.csv). Source data for Figure 9 in the paper.
    * [`/data/ReservesBalancesData.xlsx`](data/ReservesBalancesData.xlsx). PEW Charitable Trusts historical data on all 50 states total balances and rainy day fund balances from 2000 - 2023. "[Fiscal 50: State Trends and Analysis: Reserves and Balances](https://www.pewtrusts.org/en/research-and-analysis/data-visualizations/2014/fiscal-50#ind5)", updated May 17, 2023 (accessed May 26, 2023). Data can be downloaded from the PEW site from this URL (https://www.pewtrusts.org/-/media/data-visualizations/interactives/2016/fiscal-50/docs/2013/ReservesBalancesData.xlsx?v=20230322).
    * [`/data/state_taxtype.csv`](/data/state_taxtype.csv). Data on 50 states plus District of Columbia state employment income tax type.
