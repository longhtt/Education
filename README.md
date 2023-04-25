# DATA 3320 (project 2: Education Inequality)

## Purpose
This project is to look at school performances on ACTs and SATs test score and see if they can be predicted by certin factors provided from data from EdGap and the National Center for Education Statistics (NCES)

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
