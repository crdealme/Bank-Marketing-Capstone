# Bank-Marketing-Capstone

# Introduction

A Portuguese Banking Institution performed, along the years, several direct marketing campaingns designed to attract more clientes. However, the institution is not able to evaluate if the marketing campaigns were successfull. There are also no analysis concerning the segments of clients with higher to subscribe to a term deposit.

# Problem Statement

Questions to be answered/addressed:
    - Can we predict wheter a client will subscribe a term deposit based on the variables collected during the direct marketing campaign? Based on past data, how accurate can we be?
    - What are the common features of clients that are more likely to subscribe a term deposit?
    - In an overall perspective, can we say that the formers marketing campaings were successful?

#  Strategy/expected results:

Strategy/expected results:
    - The strategy consists in preparing the data (with the suitable pipelines) to build a classifier that assigns the probabiblity that a client will subscribe to a term deposit. Based on this probability there will be defined a threashold to determine (like a hard classification problem) the clients that subscribed to the service
    - These clients will be separated in groups to define the segments more likely to subscribe
    - With these perspectives the overall numbers will be considered to understand if the campaigns were successful

#  Metadata:

1 - age (numeric)
2 - job : type of job (categorical: ‘admin.’,’blue-collar’,’entrepreneur’,’housemaid’,’management’,’retired’,’self-employed’,’services’,’student’,’technician’,’unemployed’,’unknown’)
3 - marital : marital status (categorical: ‘divorced’,’married’,’single’,’unknown’; note: ‘divorced’ means divorced or widowed)
4 - education (categorical:‘basic.4y’,’basic.6y’,’basic.9y’,’high.school’,’illiterate’,’professional.course’,’university.degree’,’unknown’)
5 - default: has credit in default? (categorical: ‘no’,’yes’,’unknown’)
6 - housing: has housing loan? (categorical: ‘no’,’yes’,’unknown’)
7 - loan: has personal loan? (categorical: ‘no’,’yes’,’unknown’)
8 - contact: contact communication type (categorical: ‘cellular’,’telephone’)
9 - day: last contact day of month (1 to 31, depending on the number of days in the month)
10 -  month: last contact month of year (categorical: ‘jan’, ‘feb’, ‘mar’, …, ‘nov’, ‘dec’)
12 - day_of_week: last contact day of the week (categorical: ‘mon’,’tue’,’wed’,’thu’,’fri’)
13 - duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y=’no’). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.
14 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
15 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
16 - previous: number of contacts performed before this campaign and for this client (numeric)
17 - poutcome: outcome of the previous marketing campaign (categorical: ‘failure’,’nonexistent’,’success’)

# Data Science Steps in the Project

1. Data Exploration
2. Data Visualization
3. Data Preprocessing
4. Implementation and Refinement - Model
5. Model Evaluation and Validation
6. Reflection - Answering the Business Questions
