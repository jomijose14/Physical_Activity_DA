# Physical_Activity_DA
## Overview
This repository contains the code and documentation for analyzing the Physical Activity Monitoring dataset using data science research methods. The dataset tracks information about 18 different physical activities among 9 subjects, including eight males and one female. The activities are monitored with the help of three wireless Colibri IMUs (Inertial Measurement Units) and one Heart Rate Monitor (HR monitor). The IMU sensors are strategically placed on the chest, the dominant side's ankle, and the dominant arm (hand) above the wrist.

The analysis aims to understand and showcase how active individuals are based on their physical activities. The process involves data loading, cleaning, exploratory data analysis, hypothesis testing, and the use of multivariate linear regression to model continuous variables such as heart rate and hand temperature. The ultimate goal is to build a model that can predict the performed activity based on input variables.

## Dataset Information
**Data Collection Protocol:** The DataCollectionProtocol file contains detailed information about the data collection process, including the placement of sensors and the protocol followed.

**Description of Activities:** The DescriptionOfActivities file provides a list of optional activities, in addition to the 12 distinct activities outlined in the protocol. In total, there are 18 performed activities captured in the dataset.

**Data File:** The actual data is available in the .dat file, containing records of the monitored activities.

## Analysis Process
**Data Loading and Cleaning:** The first step involves loading the dataset and cleaning any inconsistencies or missing values.

**Exploratory Data Analysis (EDA):** Exploring the dataset to understand the distribution of variables, identifying patterns, and gaining insights into the data.

**Hypothesis Testing:** Determining which variables (e.g., heart rate, temperature, acceleration) provide the most useful insights. This step involves statistical hypothesis testing.

**Multivariate Linear Regression:** Building a model using multivariate linear regression to predict continuous variables like heart rate and hand temperature. This model will further help in determining the performed activity based on input features.
