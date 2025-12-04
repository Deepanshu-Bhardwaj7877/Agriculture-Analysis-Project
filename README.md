#  Agriculture Analysis

### Dashboard Link : https://app.powerbi.com/groups/me/reports/94c33d63-f165-43ab-ae4c-e29ff9aa6984/a036dd378108927bc7d9?experience=power-bi

## Problem Statement

This dashboard helps farmers and agricultural analysts understand crop performance better. It helps them know which crops are suitable for which season and location based on environmental factors like rainfall, temperature, and humidity. Through different visualizations, they can get to know their areas for improvement and thus can enhance their crop selection and resource management by identifying these patterns. It also lets them know the average rainfall by year and season, so by using this dashboard to identify these trends, they can further work on optimizing irrigation and mitigating the risks of adverse weather conditions.

Since crop yield is heavily dependent on climatic conditions, a thorough analysis of these factors is crucial for maximizing agricultural productivity. Also, since there are significant variations in rainfall across different locations and years, they must try to select crops that are well-suited to the local climate.


### Project Workflow: Steps to Create the Agriculture Analysis Project 

- Step 1: Create an Amazon S3 Bucket and Upload Data

- Step 2: Create an IAM Role for Snowflake Access

- Step 3: Create an Integration Object in Snowflake

Process: Create a STORAGE INTEGRATION object using SQL commands. This object establishes a secure, password-less connection between Snowflake account and the AWS S3 bucket.

Configuration: provided the S3 bucket path and the ARN of the IAM role you created.

Update Trust Policy: After creating the integration, Snowflake provide an External ID and a Snowflake IAM User ARN.Go back to the IAM role in AWS and update its "Trust Relationship" policy to include these two values. This finalizes the secure handshake between the two services.

- Step 4: Load Data into a Snowflake Table

- Step 5: Transform Data in Snowflake

Process: This is where i clean the data, handle missing values, change data types, or create new calculated columns. For this project, I would ensure columns like Rainfall, Temperature, Yields, etc., are in the correct numeric format and that date/year columns are clean.

- Step 6: Load Data from Snowflake into Power BI Desktop

- Step 7: Create "Rainfall Analysis" Chart

- Step 8: Create "Average Rainfall by Year"  Chart


- Step 9: Create "Average Rainfall by Season" Chart


- Step 10: Create "Average Rainfall by Crops" Chart


- Step 11: Create "Average Rainfall by Location" Chart


 ![Image](https://github.com/user-attachments/assets/f67979e2-9068-4f4f-8ab2-4ac9b5b51ece)

- Step 12: Create "Temperature Analysis" Chart

- Step 13: Create "Average Temperature by Year"  Chart


- Step 14: Create "Average Temperature by Season" Chart


- Step 15: Create "Average Temperature by Crops" Chart


- Step 16: Create "Average Temperature by Location" Chart

![Image](https://github.com/user-attachments/assets/0237649c-f510-4b1b-ad50-3bddbd7d3d6a)

 - Step 17: Create "Humidity Analysis" Chart

- Step 18: Create "Average Humidity by Year"  Chart


- Step 19: Create "Average Humidity by Season" Chart


- Step 20: Create "Average Humidity by Crops" Chart


- Step 21: Create "Average Humidity by Location" Chart

![Image](https://github.com/user-attachments/assets/e6ac5b3e-7440-4a50-b704-d2c0802215b6)

 - Step 22: Create "Yeilds Analysis" Chart

- Step 23: Create "Average Yeilds  by Year"  Chart


- Step 24: Create "Average Yeilds  by Season" Chart


- Step 25: Create "Average Yeilds  by Crops" Chart


- Step 26: Create "Average Yeilds  by Location" Chart

![Image](https://github.com/user-attachments/assets/dd98c6c5-fb37-45cd-9807-f351096205e8)



 - Step 27 : The report was then published to Power BI Service.
 
 
![Image](https://github.com/user-attachments/assets/ab514abd-c66a-4f08-852f-f3ee7267a4a4)

# Snapshot of Dashboard (Power BI Service)

![Image](https://github.com/user-attachments/assets/2173ba4d-6a74-436a-95ce-070c7d190be5)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Image](https://github.com/user-attachments/assets/05374486-bf2d-47b3-a32d-f39a288bcb9b)

 


           
