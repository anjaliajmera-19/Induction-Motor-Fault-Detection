# Induction-Motor-Fault-Detection
**Objective**

The objective of this project is to analyze induction motor operating conditions and identify faults, particularly broken rotor bar faults, using electrical and mechanical parameters.

The project uses motor simulation data to study variations in current, voltage, torque, speed, and slip under healthy and faulty operating conditions. It aims to understand the differences between normal motor operation and fault conditions through data analysis and visualization.

**About the Dataset**

The project uses three CSV datasets:

1. Motor Fault Dataset (motor_fault_dataset.csv)

Contains 21,239 observations with the following parameters:

Time

Current

Voltage

Torque

Speed

Slip

Label (Healthy / Broken Rotor Bar)

2. Healthy Motor Dataset (healthy_motor_labeled.csv)

Contains 11,903 observations representing normal induction motor operating conditions.

3. Broken Rotor Bar Dataset (broken_rotor_bar_labeled.csv)

Contains 9,336 observations representing induction motor operation under broken rotor bar fault conditions.

The datasets contain electrical and mechanical measurements used to analyze and compare different motor operating conditions.

**Method**

The project consists of the following main steps:

Data Loading: Importing the motor datasets using Pandas.

Data Exploration: Examining dataset dimensions, column information, statistical summaries, and data distributions.

Data Quality Analysis: Checking for missing values and duplicate records.

Fault Distribution Analysis: Visualizing the distribution of healthy and faulty motor samples using count plots.

Parameter Distribution Analysis: Using histograms and KDE plots to study current, voltage, torque, speed, and slip.

Motor Condition Analysis: Examining electrical and mechanical parameter variations under healthy and broken rotor bar conditions.

**Requirements**

To run the project, install the following libraries:

NumPy

Pandas

Matplotlib

Seaborn

Install using:

pip install numpy pandas matplotlib seaborn

**Motivation**

Induction motors are widely used in industrial applications, and their reliable operation is essential for maintaining system efficiency and avoiding unexpected failures.

Broken rotor bar faults can affect motor performance and operating characteristics.

This project aims to:

Understand the operating characteristics of a healthy induction motor.

Analyze the effect of broken rotor bar faults.

Study variations in current, voltage, torque, speed, and slip.

Explore data-driven approaches for induction motor condition monitoring.

Fault Conditions Analyzed

Healthy Motor: Normal operating condition without rotor bar faults.

Broken Rotor Bar: Fault condition associated with damage to the rotor bars.
