# Data-Analysis


## Introduction
Dataset Description
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

‘ScheduledDay’ tells us on what day the patient set up their appointment. ‘Neighborhood’ indicates the location of the hospital. ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família. The encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up. The other attributes are denoted with either a 1 or 0.1 if the attribute is true and 0 its its false eg No Scholarship 1 means the person is on scholarship and 0 means they are not on scholarship

# # #Question(s) for Analysis
What are the main factors influencing whether or not a person will show up for an appointment?
Firstly we will analyse the relationship between sickness and probability of person to show up? Then analyse How else does the attributes independent of a person's condition affect thier probability to show up From this we will be able to see the most important factors that influence whether or not a person is likely to show up and any recommendation to increase patient turn up rate

Dependent variable : No show
Independent variables : neighbourhood , message recieved , Gender , ScheduledDay ,AppointmentDay Age Neighbourhood Scholarship Hipertension, Diabetes ,Alcoholism, Handcap ,SMS_received

## Goal : Trying to find the impact of each of these factors on influencing a person's turn up for an appointment
