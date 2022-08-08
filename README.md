# no_show_appointment_analysis

dataset and investigation.

# Project: Investigate a Dataset - No-Show Appointment

## Table of Contents

- Introduction
- Data Wrangling](Data Wrangling
- Exploratory Data Analysis
- Conclusions


## Introduction

### Dataset Description 

> The data contains medical appointments records of patients in Brazil and it focuses on whether patients usually show up on their appointment or not. The data is made up of 110527 rows and 14 columns. Below are the columns and a brief explanation of what they mean. 

> **PatientID:** personal identification of the patient

> **AppointmentID:** Identification of each appointment

> **Gender:** Identifies the patient as either Male or Female

> **Age:** How old is the patient

> **Neighbourhood:** The patient Area of location

>**(Hipertension, Diabetes, Alcoholism, Hadncap):** These columns indicate either 1 or 0 to indicate if the patient has the disease or not (1 means yes he/she has it, 0 means he/she does not have it)

>**SMS_received:** This indicates whether patients received an sms to remind him or her about the appointment

>  **ScheduledDay:** tells us on what day the patient set up their appointment.

> **Neighborhood:** location of the hospital.

> **Scholarship:** indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.

> **No-show:** Tell us whether the patient showed up per the schedule or did not show. Yes indicates did not show up and No indicate did show up


### Question(s) for Analysis
> 1. Which particular disease patients show up more for their appointment. <br>
> 2. Does the scholarship package has an influence on the show up?
> 3. Which age group usually show up the most. Or does age affect the show up? <br>
> 4. Does SMS alert influence the show up 



## Conclusions

> Analysis from the EDA step shows that:

> Patients who are negetive for either diabetes or hipertension are more show up for their appointment than those who positive for the two conditions

> Also, it was found that gender plays a role on the show since more females show up more than males. This can be concluded that females are more likely to show up for their appointment than males.

> Age also has influence on the show. From the analysis, more old age and children show up for their appointment than young adults.

> Last the scholarship package turn not have an influence on the show up since patients with scholarship package show less than those with scholarship package

## Limitation
> More data is need to be able to know which particular day amongst the days of the week do people set as their appointment and what is the show up pattern amongst the days of the week

> With regards to the data collection, there has no been any mention of how it was collected, there is question of the validity of the data
