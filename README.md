# Finlens by KITA KOD 

An automating Shariah Compliance Assessment for PLCs

# Table of Content
1) Introduction
2) Backend Code
3) LLM
4) 

# Introduction
This project aims to provide a solution to identify Shariah Compliance of a company by simply uploading an annual financial report pdf file in a website. 

# Installation
Install the required dependencies

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
  
# Creating Assistants
To perform data extraction, assistants are created using OpenAI's API. These assistants are trained to understand instructions and extract relevant financial data from PDF files.
