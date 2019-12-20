# UF Salary Data

This report uses publicly-accessible salary data about the Florida State University System to generate summary statistics about UF salaries of interest to CTS-IT.  The data set is accessible at https://prod.flbog.net:4445/pls/apex/f?p=140:30:

The script automatically downloads the source dataset if it does not exist and stores it at `input/emp.csv`. To refresh this input dataset, delete `input/emp.csv` and re-run the script.


## Requirements

You'll need to install Rstudio and R to run this report. See [https://rstudio.com/products/rstudio/](https://rstudio.com/products/rstudio/). The free version is all you need.


## How to use this tool

Open the `uf_salaries.Rproj` file in RStudio and press the `Knit` button.

Every 6 months or so, delete `input/emp.csv` and press `Knit` again to refresh the data and regenerate the report.
