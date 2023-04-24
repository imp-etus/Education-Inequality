# Education Inequality

## Purpose

This project aims to measure whether school performance on the ACT and SAT tests can be predicted by socioeconomic factors, using data from EdGap and the National Center for Education Statistics (NCES).

## Data

### Sourcing

This project uses data from EdGap.org, which itself sources data from the Census Bureau's American Community survey. That data can be found [here](https://www.edgap.org/#4/37.89/-97.00). A replica of that data is saved to this github repository under `EdGap_data.xlsx`. This data set includes average ACT/SAT scores for schools along with socioeconomic characteristics of the school district, which was taken from each state's department of education or other release. 

Additionally, secondary school information is taken from the NCES, which contains basic identifying information about each school. That data can be found [here](https://nces.ed.gov/ccd/pubschuniv.asp). 

Alternatively, the EdGap data set can be accessed from the DATA 3320 Github repository [here](https://github.com/brian-fischer/DATA-3320/tree/main/education).

The NCES data is too large to be hosted on Github, and can instead be found [here](
https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0).

### Preparation

A colab notebook was used to prepare the data by splitting 20% for training & testing purposes. Those csv's are linked as `cleaned_training.csv` and `cleaned_testing.csv`, respectively. The .ipynb file labeled `Data Preparation` holds the most updated copy of that notebook.
