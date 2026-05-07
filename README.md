# FUTURE_DS_03
Marketing Funnel and Conversion Performance Analysis using Python to identify funnel drop-offs, channel performance, and conversion optimization opportunities

## Project Overview
This project was completed as part of the Future Interns Data Science & Analytics track. The goal was to analyze marketing funnel data to understand how prospects move through the funnel from initial campaign records to converted customers.

## Business Problem
A subscription or campaign-driven business needs to understand where potential customers drop off, which channels convert best, and what actions can improve lead-to-customer conversion.

## Dataset
The analysis uses the Bank Marketing Campaign dataset. The target variable is `y`, where `yes` means the customer subscribed/converted and `no` means they did not convert.

## Tools Used
- Excel for dashboard/report creation
- Python for data cleaning, KPI calculations, and analysis logic
- GitHub for project documentation

## Funnel Definitions
- Visitors / Prospects: all campaign records
- Reached via Known Channel: contact method is known (`cellular` or `telephone`)
- Engaged Leads: call duration of at least 180 seconds
- Warm Leads: engaged leads or customers with previous campaign interaction/success
- Converted Customers: customers who subscribed (`y = yes`)

## Key KPIs
- Total Prospects: 45,211
- Converted Customers: 5,289
- Overall Conversion Rate: 11.7%
- Known-Channel Reach Rate: 71.2%
- Engaged Lead Rate: 50.2%

## Key Insights
- Overall conversion rate is 11.7%: 5,289 customers converted from 45,211 prospects.
- The biggest funnel leak is from prospects to known-channel reach: 13,020 prospects (28.8%) had unknown contact channel.
- Cellular is the strongest contact channel at 14.9% conversion, while Unknown performs lowest at 4.1%.
- Mar is the best month with 52.0% conversion; May is the weakest at 6.7%.
- Student customers are the highest-converting major job segment at 28.7%; Blue-Collar is lowest at 7.3%.
- Previous campaign outcome is a strong retention/conversion driver: 'success' prospects convert at 64.7%.

## Recommendations
- Prioritize cellular campaigns and reduce unknown-contact records by improving lead data capture before campaign launch.
- Focus follow-up campaigns on previously successful contacts and warm leads, because prior positive engagement strongly increases conversion.
- Review weak months and campaign timing; shift budget toward high-conversion periods and run experiments during low-performing months.
- Limit excessive repeat contacts: compare 1-contact and 4+ contact segments to avoid fatigue and improve lead quality.
- Build segment-specific messaging for high-converting age, job, and balance groups while testing offers for low-converting segments.

## Excel Analysis File:  https://1drv.ms/x/c/5c2c858b1e9fc3ce/IQBfrr-FVKXjSJcPc8aVP-qbAaEt6W8V9yi96me6stKmV7g?e=tAuLby

## Author
Serge Junior Benya  
Data Science & Analytics Intern – Future Interns
