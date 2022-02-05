# Simulating_Pandemic_Flu_Spread

## Note:
This repository is for personal back-up purpose. Download, copy or use of any code will be considered a violation of Georgia Tech's Honor Code.

## Problem Statement:

In this simulation project, we consider the spread of a pandemic flu in a classroom of 21 elementary school
kids. At the beginning of the simulation, 20 of the kids are healthy and susceptible to the flu, and one kid
(Tommy) is infected with the flu virus. The infected kid has the chance of contacting everyone in the
classroom and spreading the flu to anyone he meets, at a probability p of 0.02 per day. For our initial
deterministic model, we assume that, as in the problem description, any infected person will be infectious
for 3 consecutive days. On any of the three days, any individual susceptible kid has a chance of 0.02 of
getting infected by the infectious person. After 3 days of infection, the infected kid will fully recover and
is immune to the flu.

The main questions that we would like to answer for this project include:

* How can we model the development of the infection chain initiated by Tommy over time?
* What is the distribution of student infections each day?
* How do we estimate the expected number of kids infected each day?
* What is the maximum number of kids that can stay infected on any given day?
* How long will the flu spread last among the students?
* When does the number of infections reach the peak?
* How long does the peak last?
* What precautionary measures can we recommend containing the spread of the pandemic?

To answer these questions, we divide our simulation approach into three parts:

1. Building a deterministic simulation model with the parameters given in the problem description,
such as probability of being infected, time for recovery, and capable infection scope of every
infected kid, and analyzing simulation output.
2. Creating a stochastic model to treat the key parameters given in the problem as unknown,
introduce random variables as estimators for those parameters, and simulate the results for
different distributions of the random variables in multiple replications.
3. Performing scenario and sensitivity analysis to determine the impact of e.g. class size, infection
rate, required recovery time to develop immunity. Based on this, we can recommend relevant
protection and precaution measures, e.g. isolation policy, optimal class size, intervention activity,
etc. to contain the pandemic.

## Selected Results
Selected results from employed methodology are shown below. For full results, please refer to the uploaded report. Thank you. 

### Deterministic Simulation
![image](https://user-images.githubusercontent.com/70823162/152627708-2c8bfae1-32e4-43e8-b1d2-724bd298beb5.png)

### Stochastic Simulation
![image](https://user-images.githubusercontent.com/70823162/152627724-f387d1f2-67c4-46bd-9817-b1d71d976274.png)
![image](https://user-images.githubusercontent.com/70823162/152627735-aa247361-309a-4b64-88bf-625511e9e6e1.png)
![image](https://user-images.githubusercontent.com/70823162/152627740-d0cbfbdf-e4d3-4f31-8c88-9c29375bd055.png)

### Sensitivity Analysis
![image](https://user-images.githubusercontent.com/70823162/152627757-89a7e51b-0032-4611-83b1-940f02d92f45.png)
![image](https://user-images.githubusercontent.com/70823162/152627761-94a0f6a2-732a-4fa2-aba5-05140cace1ef.png)
![image](https://user-images.githubusercontent.com/70823162/152627769-da5fe6c7-d2c0-47ad-9178-0615af2f6ace.png)

## Code Description
Introduction to the project folder

## 01_Deterministic_Model.ipynb : 
The code and results for the deterministic model. This corresponds to the “Main Findings - Deterministic Simulation” part in our final report.

## 02_Stochastic_Model.ipynb : 
The code and results for the stochastic model. This corresponds to the “Main Findings - Stochastic Simulation” part in our final report.

## 03_Sensitivity_Model.ipynb : 
The code and results for the sensitivity analysis. This corresponds to the “Main Findings - Sensitivity Analysis” part in our final report.
