# UF Salary Data

This report uses publicly-accessible salary data about the Florida State University System to generate summary statistics about UF salaries of interest to CTS-IT.  The data set is accessible at https://prod.flbog.net:4445/pls/apex/f?p=140:30:

The script automatically downloads the source dataset if it does not exist and stores it at `input/emp.csv`. To refresh this input dataset, delete `input/emp.csv` and re-run the script.
