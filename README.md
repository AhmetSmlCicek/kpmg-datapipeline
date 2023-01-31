# Project Description 

The goal of the project is to extract valuable information from industry-wide collective labor agreements in Belgium and detect important legal changes 
regarding employees' rights.

The agreements are published in pdf format and classified based on the topic they cover. 

The end users consist in lawyers who advise their client about upcoming changes. 

# Added Value 

The added value would be notifying lawyers before anyone else about important upcoming changes in employees' economic and social rights. As an extra value, to provide a simple comparision between new socio-economic rights and previous respective rights. 

# Approach

The project can be divided into three main tasks: Donwloading pdfs and extracting meta-data, Getting text with OCR, Extracting important points with ML model.

A data pipeline has been created to deliver the end result. The tasks are organized in a workflow with help of Apache Airflow and everything containerized with Docker. 