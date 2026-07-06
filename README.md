# theCoffe.co Dashboard:

Breif one line desc

REWORD: `The primary objective of this project is to perform an in-depth Exploratory Data Analysis (EDA) to understand and analyze customer behavior based on transactional data. `

linkcode
RFM - Recency Frequency Monetary
`RFM is a method used for analyzing customer value. It is commonly used in database marketing and direct marketing and has received particular attention in retail and professional services industries.`

RFM stands for the three dimensions:

Recency – How recently did the customer purchase?
Frequency – How often do they purchase?
Monetary Value – How much do they spend?

## Project Structure:

1. **Project Overview:** 
    1. `0_data/` - Where all dataset files are contained, broken down further into different categories: 
        - `raw` - Where raw preprocessed datasets are imported to. 
        - `Processed` - Where raw datasets are processed into complete workable datasets.
        - `Synthetic` - Where the final dataset sits, a synthetic dataset generated using the synthetic dataset vault. 

    2. `1_code/` 
    3. `2_dashboard/` 
    4. `3_notebooks/` - The notebooks folder is used as an inspection envrioment for potential datasets. Unsuccessful datasets are discarded, whereas datasets that were successful were moved on towards pre processing within the '0_data/' folder.  

3. Setup/Install Steps: 

4. How each component connects:

5. Project Usage:

6. Project Pipeline Approach: 
Combine twin dataset. 
Add syntethetic columns from df3
reneame generic feilds to enhance readability
feed curated dataset into SDV to generate synthetic dataset. 

