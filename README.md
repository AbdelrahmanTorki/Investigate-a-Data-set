# Investigate-a-Data-set

## Overview
Investigation of the patients of no show appointments data set consisting of 100k medical appointments in Brazil.

## Files Description:
1. .ipynb_checkpoints Contains the checkpoints of the investigation process in the 'No Show Appointments Investigation.ipynb', might help in reproduction
2. No Show Appointments Investigation.ipynb 	chore: jupyter notebook containing all investigation code, viz, and analysis
3. No Show Appointments Investigation.html 	chore: the 'No Show Appointments Investigation.ipynb' rendered as HTML
4. no_show_appointments.csv 	The dataset used in the investigation 

## No Show Appointments Data:

### Overview: 

This dataset collects informationfrom 100k medical appointments in Brazil and is focused on the 
question of whether or not patients show up for their appointment.
A number of characteristics about the patient are included in each row.
* ‘ScheduledDay’ tells us onwhat day the patient set up theirappointment.
* ‘Neighborhood’ indicates thelocation of the hospital.
* ‘Scholarship’ indicateswhether or not the patient isenrolled in Brasilian welfareprogram Bolsa Família.
* Be careful about the encodingof the last column: it says ‘No’ if the patient showed up to their appointment, 
  and ‘Yes’ if they did not show up.
  
### Reference: 
https://www.kaggle.com/joniarroba/noshowappointments

### Notes:
The dataset may not be identical to the one at kaggle, so it's best to download the .csv file along the analysis

