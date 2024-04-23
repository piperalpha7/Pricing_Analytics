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


## KPI's

![image](https://github.com/piperalpha7/Pricing_Analytics/assets/94968239/9a704c2e-c2ca-490b-94f5-5478851d150d)


## Insights and Recommendations
1.
![image](https://github.com/piperalpha7/Pricing_Analytics/assets/94968239/59b18fbe-05cd-4383-a817-5cff4ef7c3f0)

👉 Good Y-O-Y growth.

👉 Insurances written throughout the year reach its peak in March and then descend, hitting bottom in December. This could be due to the approach of the financial year end. Hence Ensure we have marketing campaigns targeting towards engaging customers throughout the year.

👉 Before the 1st of May 2019, policies who have an exposure less than 1 result in lost net earned premium of £2.3M(~12.43% ↓). Check for policies before 1/5/2019 to see if people stopped their policies midway and why?


2.
![image](https://github.com/piperalpha7/Pricing_Analytics/assets/94968239/3b5898e9-a50d-4d95-9a9a-7de4e76f0e0b)

👉 Sold around 3000 lesser ‘Commuting and Social’ policies at a lower average price resulting in a loss of premium of around £1.7M(~16%↓), compared to last FY.

👉 Maintaining £401. 85(avg price) for C & S policy would have got our written premium to around £10.08m (~11%↓)

👉 Hiking the average price of SDP policies to around £350 would have increased our net premium to around £5.92m(~2% ↑) 



 3.
 ![image](https://github.com/piperalpha7/Pricing_Analytics/assets/94968239/857d4960-a3e4-4e81-bdb6-7b67023bf254)

👉 Seniors prove to be the safest drivers with an average NCD of around 8 years.

👉 South East’, ‘North West’ and ‘Yorkshire’ constitute to around 40% of the total policies


4. 
![image](https://github.com/piperalpha7/Pricing_Analytics/assets/94968239/650de142-a1fd-4329-8534-43546f99bb32)

![image](https://github.com/piperalpha7/Pricing_Analytics/assets/94968239/049047e8-7fc9-4761-939e-ef1929a87ee2)


👉 ‘London’ region has an average claim size lesser than ‘Yorkshire’ and ‘North-East’ yet has higher premiums (~25% and ~14%  respectively). Restructuring 
    of pricing is needed here.

👉 CTM sells the greatest number of Policies. Yet the average policy value is way lower than some other aggregators, thereby causing a fall in the net average. Need to go over the commissions to improve net written premium


## Claim Predictors

Identified the most probable claim predictors by having a close look at their relationship with 'average claim size'.

To put the results out in 1 sentence:

‘ A male who is aged 18-35 years, with a no claim discount between 0-2 years, parks his vehicle on the road, takes a ‘Insured + Parent’ entitlement and a comprehensive cover tends to have an average claim amount of £1280.23 and total claim of around £1.3M'













   


