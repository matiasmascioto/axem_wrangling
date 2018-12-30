# AXEM *(Data Wrangling)*

*keywords: data wrangling, python, jupyter notebook, pandas, excel, csv*

This project cleans a dataset with information about argentinian soccer players around the world. The original dataset is an Excel file, with dirty and unnormalized data. Wrangling this data generates a cleaner and more easily workable dataset (in .csv).

## Datasets
### Input
*  */data/input/axem_2018.xlsx*: [AXEM - December 2018](https://wetransfer.com/downloads/d75712ef256560fe86403e97cce269d020181219165022/3f3ec4?fbclid=IwAR1JiFmmlJPkEOvVZOH3VviGhy16ZsiPN_hJvMjtsfezT_ogMzlWkuRu-NU) - [Facebook post](https://www.facebook.com/notes/futbolistas-argentinos-axem/archivo-axem-diciembre-2018/2307096119567319/)
*  */data/input/country-codes.csv*: [Country codes](https://github.com/datasets/country-codes)

### Output
*  */data/output/axem\_2018\_processed.csv*: cleaned and normalized dataset with argentinian players data.
*  *data/output/trayectorias.csv*: dataset with the players career

## Other files
*  *axem_wrangling.ipynb*: Jupyter Notebook that contains details and codes for the data wrangling process.
*  *axem_wrangling.yml*: Configuration file