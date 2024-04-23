# Pricing Analytics

I did this pricing analytics project, based on a dummy dataset from a company. This is the reason why, I would not be able to upload the dummy dataset or the Power BI files. But, I got some good exposure to Data Cleaning and could recommend some pricing strategies.

## Tools Used
👉 Python(Pandas)

👉 MS-Excel(Pivots and Lookups)

👉 PowerBI(Dashboard)

👉 MS-PowerPoint(Presentation)



## Dataset

Dataset comprised of Car Insurance policies(40 Columns and 100000 rows)


## Data Cleaning

Some of the data cleaning steps I foolwed are as follows:-

1. Eliminated rows where the 'policy' was in force before the vehicle was purchased

![image](https://github.com/piperalpha7/Pricing_Analytics/assets/94968239/6cc324dc-6aa3-46bf-8f53-a016afc93445)

2. Eliminated rows where policy holders were residents of a country more than their age.

![image](https://github.com/piperalpha7/Pricing_Analytics/assets/94968239/06c85a55-0604-401c-bec8-b609ac428abf)

3. Eliminated ambiguous 'vehicle purchase date' rows

![image](https://github.com/piperalpha7/Pricing_Analytics/assets/94968239/312abf7e-2440-4e1e-9e62-21bf3be81068)


4. In certain cases, vehicle_age was -1 years...To rectify this watched the dataset closely and found the average vehicle value for vehicle age of 1,2,3 etc. Found that the average vehicle value of 1 year old vehicle was closest to the vehicle with age -1. Hence imputed -1 to 1

![image](https://github.com/piperalpha7/Pricing_Analytics/assets/94968239/c792fd10-c18b-451e-b544-97f0c048b0f1)

5. Eliminated customers where it was impractical for a customer to hold a licence considering his age. In this example below a customer aged 26 years cannot be holding a licence from 25 years.

![image](https://github.com/piperalpha7/Pricing_Analytics/assets/94968239/46a28d99-dbb0-4cd7-96c1-e8cdc474a9f5)



   


