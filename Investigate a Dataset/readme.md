# Investigate a Dataset - Identifying Factors that Predict Missed Appointment Among Patients in Brazil


## Project Overview
In this project, I analysed the *[No-show appointments](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv) dataset to identify factors that predicts if a patient will show-up for scheduled appointment.*
**Python** and **Jupyter Notebook** was used for this analysis.
### Requirements
* Python
* Pandas
* Numpy
* Matplotlib

### [Dataset](https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub)
The *No-show appointments* dataset collects information from 100,000 medical appointments in Brazil. A number of
characteristics about the patient are included in each row. The variable included in the dataset are *patient ID, appointment ID, gender, scheduled day, appointment day, neighbourhood, scholarship, hypentention, diabetes, alcoholism, handicap, SMS received and no-show*. 
* *ScheduledDay* tells us on what day the patient set up their appointment.
* *Neighborhood* indicates the location of the hospital.
* *Scholarship* indicates whether or not the patient is enrolled in Brasilian welfare program [Bolsa Família](https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia).
Note that the 'No-show' column says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

## Summary of Findings
In response to the analysis questions posed, the findings indicates the following.
1. What factors are important to predict if a patient will show up for scheduled appointment?<br>
> *age, gender and scholarship* are important to predict if a patient will show for appointment.

2. Is duration (appointment day - scheduled day) associated with no-show?<br>
>Yes, duration is associated with no-show. More patients showed for appointments with a duration that is shorter than 20 days.

Based on the results from this analysis, it is recommended that *shorter duration* be given to patients seeking appointments. Also, SMS or email reminder should be considered are targeted to patients who are more likely to miss appointments. These includes those 10+ years old, females and people not on scholarship.

## Relevant Links
1. [View report](Investigate a Dataset/Investigate%20a%20Dataset.ipynb) in Jupyter Notebook.
2. [View report](Investigate a Dataset/Investigate%20a%20Dataset.html)
3. [Dataset](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv) in CSV.

*This project was completed to fulfill the requirement for [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) at Udacity.*
