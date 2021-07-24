# Medical Appointments Data Analysis

## Introduction : 

> In this project we will analyze a dataset of Medical Appointments mainly regarding if the patient will show up or not to the appointment.
>
> The dataset contains 14 attributes which are ( Patient Id , Appointment ID , Gender , Appointment Day , Scheduled Day , Age , Neighborhood , Scholarship , Hypertension , Diabetes , Alcoholism , Handicap , SMS_received , No-show ). 
>
> No - show attribute is the main dependent variable we're investigating it shows if patient came to appointment or not.

## Analysis Outlines  : 

- Data Wrangling
- Cleaning Data
- Asking Questions and Visualizing Results
- Build up Conclusions

### Data Wrangling  & Cleaning :

First , We load the data using pandas and apply some functions to explore the dataset such as (shape , info , describe to get some summary statistics.)

Then Cleaning Data steps which are:

1. Naming Columns to more clean format.
2. Missing Values check  (There is no null values detected) 
3. Duplicated Rows         (The Data set is free of Duplicates.)
4. Datatypes Errors         (Data Types Errors Detected in Scheduled_Day and Appointment_Day then modified.)
5. Check if there is incompatible value    (Negative value in Age attribute is detected and replaced by mean ages.)
6. Modify No_show attribute so as to be used in visuals  (Modify the values in No_show column to be zeros and ones instead of yes and no to be able to be used easier in the next step of Exploring Data with Visuals.)



### The main Analysis Questions are : 

1. What is the percentage of showed up to the not showed up patients ?

2. What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment ?

   ​	In this Question we try to get relation between showing up in appointment and other data attributes such as :

   ​	Age , Gender , Diabetes and Scholarship.

### Note : Visual Results are shown in the Jupyter Notebook

### Conclusions :

> From our previous study we found out that the percentage of showed patients is larger and equal to 79.81% while that of not showed is 20.19%.
>
> The mean Age of showed patients is about 39 versus the mean Age of not showed ones 35 years.
>
> The number of female patients is larger than males , but on studying the not showed people the mean number of males is nearly equal to that of females.
>
> On studying the diabetes effect on patient to show or not we found out it's not a factor that determine the patient status.
>
> The people on scholarship are most likely not to show up in an appointment with percentage 23.7% versus no scholarship with percentage 19.8%.





