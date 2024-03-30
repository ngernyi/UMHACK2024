# Finlens by KITA KOD 

An automating Shariah Compliance Assessment for PLCs

# Table of Content
1) Introduction
2) Installation
3) Data Preproccesing
4) Data Extraction Functions
5) Creating AI Assistants
6) Connecting backend and frontend using FLASK


# Introduction
This project aims to provide a solution to identify Shariah Compliance of a company by simply uploading an annual financial report pdf file in a website. 

# Installation
Install the required dependencies

# Usage
Run the app.py file to run the Python Flask server to start

# Data Preproccesing
To increase the accuracy of the extraction by AI, a data preproccesing step is taken. The pdf file will be segmented by finding the keywords of the statements that contain the data that we want to extract. By selecting only the relevant pages in the pdf file, the scope for the AI to extract will be minimized, hence increase the accuracy.

# Data Extraction Functions
This project provides the following functions for extracting financial data:

- revenue_extractor: Extracts revenue data from PDF files.
- profit_extractor: Extracts profit or loss data from PDF files.
- asset_extractor: Extracts total asset data from PDF files.
- cash_extractor: Extracts cash flow data from PDF files.
- current_debt_extractor: Extracts current debt data from PDF files.
- non_current_debt_extractor: Extracts non-current debt data from PDF files.
- principal_activity_extractor: Extracts principal activities data from PDF files.
- cash_flow_extractor: Extracts cash flow compliance data from PDF files.
  
# Creating AI Assistants
To perform data extraction, assistants are created using OpenAI's API. These assistants are trained to understand instructions and extract relevant financial data from PDF files.

# Connecting Backend and Frontend using Flask and AJAX
After the data are extracted from the AI assistants, the data are sent to the frontend from backend using FLASK, specifically using 'action' and 'method' to complete the connection between frontend and backend. On the other hand, when frontend have data that needed to transfer to backend, AJAX from JavaScript will be utilized.

# Data Storage
Wherever data that needed to be saved, it will be saved into JSON format.



