# Lending-Club-Project
This project focuses on cleaning, optimizing, and analyzing Lending Club data to better understand loan performance and customer behavior.

🔧 Project Overview

The dataset contains raw Lending Club records, which require preprocessing to make it suitable for analysis.
Our goal is to clean the data, organize it into meaningful DataFrames, and extract insights about loan repayments and defaults.

🚀 Key Steps

.Data Cleaning

.Renamed inconsistent column names for better readability

.Removed duplicate records to ensure data integrity

.Dropped rows with missing (NULL) values to improve accuracy

.Data Optimization

Segregated the raw dataset into 4 different DataFrames for targeted analysis:

loans → General loan details

loans_repayments → Records of repaid loans

loans_defaulters → Customers who defaulted on loans

total_customer → Unique customer information

Analysis

Verified and tracked loan defaulters

Ensured consistency across different DataFrames for reliable insights

Outcomes

.A clean and well-structured dataset ready for analysis

.Clear identification of loan defaulters and repayment trends

.Optimized DataFrames for further modeling or dashboarding
