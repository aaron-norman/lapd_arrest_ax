# lapd_arrest_ax
An EDA on the LAPD Crime Data from 2020 to 2024

Downloading 288101 rows (75MB) of data. 
Setting up an anaconda environment and am now prompted to download the latest version of Anaconda navigator. 

Created an environment analytic_env which can be downloaded to re-run this analysis. 

We have the following datasets from [data.lacity.org](data.lacity.org)
1. Arrests:
   - [Arrest Data from 2010 - 2019](https://data.lacity.org/Public-Safety/Arrest-Data-from-2010-to-2019/yru6-6re4/about_data) 
   - [Arrest Data from 2020 - Present](https://data.lacity.org/Public-Safety/Arrest-Data-from-2020-to-Present/amvf-fr72/about_data) x
2. Crimes:
   - [Crime Data from 2010 to 2019](https://data.lacity.org/Public-Safety/Crime-Data-from-2010-to-2019/63jg-8b9z/about_data)
   - [Crime Data from 2020 to present](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data)
  
   - Currently experiencing directory issues. The datasets have been moved to 'LAPD Arrests' but are not showing up when running `os.listdir()`
   
