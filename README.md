# DATA 3320 (project 2: Education Inequality)

## Description 
This project is to look at school performances on ACTs and SATs test score and see if they can be predicted by certin factors provided from data from EdGap and the National Center for Education Statistics (NCES). After created a new data set from the two data sources, created models, and graphs to show how to predict the ACT test scores

### conclusion
We are able to make predictions from certin factors about school, several socioeconomic characteristics of the school district, and basic information about each school. 

## Requirements 
must require a GitHub account and access to Colab that runs the Data Preparation and Data Analysis

## Data
This project utilizes two data sets [EdGap_data.xlsx](https://github.com/longhtt/Education/blob/main/EdGap_data.xlsx) and [ccd_sch_029_1617_w_1a_11212017.csv](https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0). The primary data set is the EdGap data set from [edgap.org](https://www.edgap.org/#5/37.892/-96.987) This data set from 2016 includes information about average ACT or SAT scores for schools and several socioeconomic characteristics of the school district. The secondary data set is basic information about each school from the [National Center for Education Statistics](https://nces.ed.gov/ccd/pubschuniv.asp). <br/>

## Data Preparation
before an analysis can be made on EdGap_data.xlsx and ccd_sch_029_1617_w_1a_11212017.csv, a clean data set is created. Following the Colab notbook [DATA_3320_Education_Inequality_Data_Preparation_Long_Tran_Thien.ipynb](https://github.com/longhtt/Education/blob/main/DATA_3320_Education_Inequality_Data_Preparation_Long_Tran_Thien.ipynb) we can see how the clean data set [clean_education_inequality_data.csv](https://github.com/longhtt/Education/blob/main/clean_education_inequality_data.csv) was created<br/>
### short summery of steps taken to prep clean_education_inequality_data.csv
1. Load the data
2. Explore the contents of the data sets
3. Renaming columns
4. Converting data types
5. Selecting relevant subsets of the data
6. Joining data frames
7. Quality Control
8. identifying missing values
9. Train test split
10. Data imputation
11. Create relevant derived variables as new columns
12. Export the clean .csv files

## Data Anaylsis
using the clean data file created from the data preperation, created a analysis notbook [DATA_3320_Education_Analysis_Long_Tran_Thien.ipynb](https://github.com/longhtt/Education/blob/main/DATA_3320_Education_Analysis_Long_Tran_Thien.ipynb)

### short summery of steps taken to prep DATA_3320_Education_Analysis_Long_Tran_Thien.ipynb
1. Introduction
2. Import libraries
3. Load clean data
4. State your questions
5. Analysis
6. Conclusion

## Authors 
Creator of repository: Long Tran-Thien

## License 
Anyone may reuse material from this repository but must credit me 'Long Tran-Thien'
