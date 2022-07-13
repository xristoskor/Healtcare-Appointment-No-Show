# Healtcare-Appointment-No-Show

<b> DESCRIPTION </b>

A patient is considered to be a no-show when they fail to be present for a scheduled appointment. For any healthcare organization, no-shows lead to higher costs and underutilization of resources, which affects the quality of service healthcare organizations provide.

In order to solve this problem, the organizations need to be able to understand why no-show patients do so.

<b> Data Description </b>

| Variable  | Type | Description |
| ------------- | ------------- | ------------- |
| Age  | Patient information: discreet  | Age of the Patient  |
| Gender  | Patient information: categorical  |  Male or female |
| Appointment Registration  | Date object  | Date of appointment registration  |
| Appointment Date  | Date object  | Date of actual appointment |
| Diabetes  | Patient information: binary  | True or false |
| Alcoholism  | Patient information: binary  | True or false |
| HyperTension	  | Patient information: binary  | True or false |
| Handicap  | Patient information: binary  | True or false |
| Smokes  | Patient information: binary  | True or false |
| Scholarship  | Patient information: binary  | True or false |
| Tuberculosis  | Patient information: binary  | True or false |
| SMS Reminder  | Patient information: binary  | True or false |
| Status  | Target: categorical  | Show or no-show |

<b>Steps to Perform: </b>

1. Explore the data to check for missing values or erroneous entries, comment on redundant features, and add additional ones if needed
2. Create a new feature called HourOfTheDay, which will indicate the hour of the day at which the appointment was booked
3. Identify and remove outliers from the age column and explain the reason behind the selected outlier treatment using an appropriate plot
4. Analyze the probability of showing up with respect to different features, create a scatter plot and trend lines to analyze the relation between the probability of showing up with respect to age or hour of the day, and describe your findings
5. Create a bar graph to depict the probability of showing up for diabetes, alcoholism, hypertension, TB, smokes, and scholarship
6. Create separate bar graphs to show the probability of showing up with respect to male or female, day of the week, and SMS reminder columns and describe your findings
7. Use different classification models to predict the show or no-show status based on the features that display the most variation in the probability of showing up
8. Evaluate the models and choose the best one for the data
