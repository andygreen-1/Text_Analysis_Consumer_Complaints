# Exploring Credit Reporting Errors: A Text Mining Analysis of Consumer Complaint Data

## Final Project for Course PPOL 566: Data Science III – Advanced Modeling Techniques, Fall 2020

This repository contains the code, source data, and written report for an analysis exploring consumer complaints about credit reporting errors. In this analysis, I use K-means clustering and LDA topic modeling techniques to explore consumer complaint text data.

You can find a brief summary of the files available in this repository below:

* text_analysis_consumer_complaints_1.ipynb: Jupyter notebook used to read in the full batch of 378,876 complaints that were filed in the Consumer Complaint database over a 12-month period, and narrow it down to the 5,000 complaints that serve as the focus of my analysis.
    * Inputs: complaints.csv
        * Note: this file is not included in the repository as it is over 280 MB in size. As a result, it’s best not to run the code in this file, as it will error out without the proper data inputs.
        * Source: [CFPB Consumer Complaint Database](https://www.consumerfinance.gov/data-research/consumer-complaints/)
    * Outputs: complaints_sample.csv
        * Note: this file is what will be used in the next code file, and it already exists in the repository so that this file doesn’t need to be re-run.
* text_analysis_consumer_complaints_2.ipynb: Jupyter notebook that contains the code for all of the analysis steps described throughout the report.
    * Inputs: complaints_sample.csv
    * Outputs: this file produces a wide array of .csv and .png outputs containing the tables and graphics used in this report. These files can all be found in the “Tables_Graphics” sub-folder in the repository.
        * Note: the code chunks that produce these outputs are currently commented out to avoid creating unexpected files on the user’s machine.
* Text_Analysis_Consumer_Complaints_Report.pdf: final written report summarizing the key findings from the analysis

