# NSDUH_Data_ML_R: 

# Machine Learning Model Development with NSDUH Data in R

The following machine learning project examines data from the National Survey on Drug Use and Health. The objective of the project was to utilize regression and classification methods to predict substance usage, particularly adolescent substance use initiation. This repository contains an analysis focusing on cocaine use. 

All data for this project was taken from the NSDUH public use files which can be found here: https://www.samhsa.gov/data/data-we-collect/nsduh-national-survey-drug-use-and-health

## Question 1:
Utilize multiple regression methods to determine if there is a relationship between the age of first cocaine use during adolescence and the following predictors: demographic variables, perceived risk of cocaine use, availability of cocaine, danger seeking, age of first alcohol use, and age of first cigarette use.

## Question 2:
Utilize classification methods to determine whether a respondent used cocaine for the first time before 18 years old (yes/no) can be effectively classified based on demographic variables, perceived risk of cocaine use, availability of cocaine, danger seeking, age of first alcohol use,
and age of first cigarette use.

## Variable Names:
DIFGETCOC: How difficult to get cocaine? Probably Impossible. Very Difficult. Fairly Difficult. Fairly Easy. Very Easy.

RSKYFQDGR: Get a real kick out of doing dangerous things? Never. Seldom. Sometimes. Always.

RSKYFQTES: Like to test yourself by doing risky things? Never. Seldom. Sometimes. Always. 
CATAGE: Age category. 12-17. 18-25. 26-34. 35 or Older.

IRALCAGE: Alcohol age of first use. (991 = Never used) 

IRCIGAGE: Cigarette age of first use. (991 = Never used) 

YODPREV: Ever had several days where you felt sad/depressed? Yes. No.

COCEVER: Have you ever, even once, used any form of cocaine? 

COCAGE: How old were you the first time you used cocaine, in any form? 

YEPRTDNG: Have you talked with parents about the danger of tobacco and alcohol? Yes. No.

RSKCOCMON: Perceived risk of trying cocaine once or twice a month. No Risk. Slight Risk. Moderate Risk. Great Risk.

RSKCOCWK: Perceived risk using cocaine once or twice a week. No Risk. Slight Risk. Moderate Risk. Great Risk.

NEWRACE2: Race: 1 = NonHisp White, 2 = NonHisp Black/Afr Am, 3 = NonHisp Native Am/AK Native, 4 = NonHisp Native HI/Other Pac Isl, 5 = NonHisp Asian, 6 = NonHisp more than one race, 7 = Hispanic.

IRSEX: Sex: 1 = Male, 2 = Female. 
