# Problem Statement
Insurance Plus++, a premium payer, wants to use predictive modeling on healthcare data to predict the occurrence of future events among their covered patients. They want to use existing data about their patients’ previous medical events to predict future events in their patient journey. Events are recorded in the standardized ICD-9 format (details here). In this challenge, the goal is to predict the next 10 events in 2014 for each patient in order of occurrence.

# Data Description
There are three files available for download: train.csv, test.csv and sample_submission.csv

The “train.csv” file contains historical patient information from Jan 2011 to Dec 2013. The “test.csv” file contains a list of Patient IDs for which we aim to predict the next 10 events for in the year 2014. Event codes should be considered to be categorical in nature, not continuous.

Variable-Description

UID-Unique Patient ID

Age-Age of the patient

Gender-Gender of the patient

Date-Date of Event

Event_Code-Event Code (ICD-9 format, the target variable of this challenge)

# Content
1. Problem Statement
2. Data preparation
3. Computing the Probability of Occurrence
4. Prediction
5. Submission
