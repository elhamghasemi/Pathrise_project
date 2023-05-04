
This repository contains a Jupyter Notebook that analyzes a dataset of people who have participated in the Pethrise course
Pathrise is an online program designed to provide job seekers in the tech industry with 1-on-1 mentorship, training, and advice. Upon successfully passing the admission process, candidates are offered a place in the program. The program begins with a free trial period of 2 weeks, after which the fellow signs an ISA to continue. The program lasts for up to a year, and if a fellow cannot find a job within that time, their contract is terminated. 

The goal of the analysis is to gain insights into the job placement process and determine whether or not a fellow will ultimately be placed at a company.
The dataset consists of 15 features:

•	id: A unique identifier for each individual in the dataset.

•	pathrise_status: The current status of the individual within the Pathrise program.

•	primary_track: The area of focus within the tech industry that the individual is pursuing.

•	cohort_tag: The specific cohort that the individual belongs to.

•	program_duration_days: The length of time, in days, that the individual has been in the Pathrise program.

•	placed: A binary variable indicating whether or not the individual has been placed in a job.

•	employment_status: The individual's current employment status.

•	highest_level_of_education: The highest level of education attained by the individual.

•	length_of_job_search: The length of time, in months, that the individual has been searching for a job.

•	biggest_challenge_in_search: The biggest challenge that the individual is facing in their job search.

•	professional_experience: The individual's prior work experience.

•	work_authorization_status: The individual's current work authorization status.

•	number_of_interviews: The total number of interviews the individual has had.

•	number_of_applications: The total number of job applications the individual has submitted.

•	gender: The individual's gender.

•	race: The individual's race.


The steps taken for the analysis include:

1-Data cleaning

2-management of missing value

3-Data visualization

4-Modeling using different algorithms such as KNN, SVM, DT, RF, and LR.


The accuracy score, confusion matrix, and classification report for each of the models are included in the Jupyter Notebook.

Files included in the repository:

-Pathrise_project.ipynb: This is the Jupyter Notebook containing the analysis.

-Data_Pathrise .xlsx: This is the dataset used for the analysis.
