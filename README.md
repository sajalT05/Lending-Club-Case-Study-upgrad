# Lending Club Case Study - Exploratory Data Analysis
<!-- > Outline a brief description of your project.-->
> This Project is an exploratory study of the data made available from Lending club. We are trying to figure out the structure of the data, get insights on various columns and find out which variables affect the outcome 'loan_status' the most i.e. which variables are stong indicators of person's tendency to default. We have to look at all the variables and finally decide on the 5 most significant variables affecting the person's tendency to default.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
  - The Project has 3 files: 
      - 'loan.csv' - It contains the raw dataset from the Lending Club
      - 'Data_Dictionary.xlsx' - It contains the definition of each variable given by Lending Club
      - 'Group_facilitator_Name.ipynb - The jupyter notebook containing the code of the exploratory data analysis carried out on the dataset
      - 'loan_columns.csv - csv file created using the first sheet of Data_Dcitionary.xlsx file
- What is the background of your project?
  -  It stems from the business need to reduce the loan defaults and increase the profit of investors
- What is the business probem that your project is trying to solve?
  -  The project aims to find the most significant variables which indicate an applicant's tendency to default and it needs to be found for the company
- What is the dataset that is being used?
  - The dataset is customer data of the lending club for the loans approved from 2008-2011. The data doesnt contain the records for loans rejected. It contains the loans which were approved. Among the approved loans, there are 3 categories i.e. Fully paid loans, charged Off or defaulted loans and Current loans which are till running. There are many other columns storing the customer and loan information.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
<!-- - Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis -->
- There are many columns in the dataset which are all empty and can be dropped
- There are many rows which which contain single values and can be dropped
- There are many behavioural columns which are not available at the time of screening and need to be removed
- There are many columns which need data type conversion and cleaning and outlier removal
- The variation of rate of defaults for each variable is shown in the below table
- <p align="center"><img src="https://user-images.githubusercontent.com/111374919/188484166-d98af3b9-7e36-471a-81d0-97f1010925dd.png"/></p> <p align="center"><img src="https://user-images.githubusercontent.com/111374919/188484254-915d3acf-7f28-4117-8192-4f9b3fa8e851.png" width="800"/> </p>

- The 5 most significant variables are 
    - sub_grade,
    - int_rate, 
    - grade, 
    - pub_rec_bankruptcies 
    - loan_amnt
- But some of these variables are highly correlated. After removing the variables with high correlation, the 5 most significant variables are
    - sub_grade
    - int_rate
    - pub_rec_bankruptcies
    - loan_amnt
    - home_ownership


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0
- jupyter - Version 1.0.0
- Matplotlib - version 3.5.3
- missingno - version 0.5.1
- numpy - version 1.23.2
- pandas - version 1.4.3
- scikit-learn - version 1.1.2
- scipy - version 1.9.0
- seaborn - version 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
<!--- This project was inspired by...-->
- References- 
  - The variable definitions and some more understanding of the dataset came from
    - https://www.cs.dartmouth.edu/~lorenzo/teaching/cs174/Archive/Winter2015/Projects/proposals/fmz.pdf
    - https://www.rubydoc.info/gems/lending_club/0.0.2/LendingClub/Loan
  - The syntax and package usage information came from
    - https://pandas.pydata.org/docs/getting_started/index.html
    - https://stackoverflow.com/
    - https://seaborn.pydata.org/index.html
<!--- This project was based on [this tutorial](https://www.example.com).-->


## Contact
- Created by Sajal Tiwari [@sajalT05] - feel free to contact.
  - Email - Sajal.tiwari05@gmail.com
- Second Member of the group, Shyam Sundar Shukla
  - Email - shyamsundarshukla1991@gmail.com


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
