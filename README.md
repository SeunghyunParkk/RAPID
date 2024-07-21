# RAPID: Real-time Alert Platform for Informed Decisions
<img src="Images/RAPID.png" alt="Example Image" width="300" />

## Table of Contents
1. Introduction
2. Features
3. Installation
4. Prerequisites
5. Usage

## Introduction

This project involves collecting drug test data from various online sources, transforming it, and applying criteria to identify harmful drug adulterants. The resulting alerts are displayed through a dashboard named RAPID (Real-time Alert Platform for Informed Decisions). RAPID aims to enhance public health by providing real-time alerts about potentially dangerous drug batches. This data-driven approach improves healthcare system preparedness, optimizes resource allocation, supports evidence-based policy development, and offers valuable insights into illicit drug trends for robust research. Data collection and transformation were done using Python, and the dashboard was created with Google Looker Studio.

## Installation

Step-by-step instructions on how to install and set up the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RAPID.git
   cd RAPID
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
   
### Prerequisites

List of prerequisites necessary for the project:

	•	Python 3.x
 	•	Jupyter Notebook
	•	Pandas
	•	Numpy
	•	Selenium

Ensure you have the required datasets:

	•	Dashboard.csv

## Usage

1.	Ensure you have the necessary dataset (Dashboard.csv) in the project directory.

   	<img src="Images/Step1.png" alt="Example Image" width="300" />
    
2.	Open the Jupyter notebook file (Monthly_Update.ipynb) and set the initial dates.

   	<img src="Images/Step2.png" alt="Example Image" width="600" />
    
3.	Run the code to gather, process the data.

   	<img src="Images/Step3.png" alt="Example Image" width="300" />
    
4. 	Add external data on Monthly_Update.csv file if there is any.
   
5.	Open the Jupyter notebook file (Criteria.ipynb) and Run to apply criteria.
    
6.	The processed data (Dashboard.csv) will have alert status based on the criteria.
 
7.	Create a dashboard using the dataset (Dashboard.csv).
   
### Dashboard Example

![Example GIF](Images/Demo.gif)

You can view the interactive dashboard [here](https://lookerstudio.google.com/embed/reporting/d4ee0e89-a8b2-4d92-9926-f69474198d63/page/p_lffrf20bjd).

## Features

List of key features included in the project:

1.	Data Collection and Transformation:
	The project collects drug test data from various online sources and transforms it using Python to ensure it is ready for analysis.

2.	Criteria-based Identification:
	Applies criteria to the collected data to identify harmful drug adulterants, enabling accurate and timely alerts.

3.	Interactive Dashboard:
	The RAPID dashboard, created using Google Looker Studio, provides an interactive and user-friendly interface to visualize alerts and trends.

8.	Data-Driven Insights:
	Offers valuable insights into illicit drug trends, supporting robust research and evidence-based policy development.

 
## Data Sources

Details about the data sources used in the project:

- [British Columbia Centre on Substance Use & UBC MDS Drugsense](https://bccsu-drugsense.onrender.com)
- [Get Your Drugs Tested](https://getyourdrugstested.com/alerts/)


## Contact Information

For any questions or concerns, please contact:

Name: Seunghyun Park

Email: seunghyun.park@mail.mcgill.ca

GitHub: https://github.com/SeunghyunParkk
