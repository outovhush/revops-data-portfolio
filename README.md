# revops-data-portfolio
Showcasing some examples of my work in sales and revenue operations

Hey there! I'm Andrew 👋

Ever heard of Revenue Operations (RevOps)? It's the rather new word in business, and it's shaking things up a bit. Imagine a superhero team where sales, marketing, and customer service all work together aligned perfectly to make more money. And the infrastructure and automation ensures that work is done in most effective and efficient ways. That's the RevOps product! More and more SMB companies are catching on, realising it's not just a fad but a real thing.

So, why am I the right person for RevOps? Well, I've done a bit of everything. I can see the big picture but also know how to get things aligned day-to-day. It's like being able to plan an awesome party and also know how to set up the decorations. I'm good at talking to different teams, understanding what they need, and finding ways to balance their needs and hit the revenue goals.

Now, let's talk about data. It's super important in on the operations side of things, but here's the thing – real world data is messy unlike what you see in the Titanic dataset. My job is to clean it up, make sense of it, and turn it into useful information. With the right tools, the CRM well set and customised, we can track everything important, get insights and make better business decisions.

Want to see how I've put all this into action? Check out some examples of my work below. It's versatile, here will be a few sections:👇🏼

* [Business Analysis and BP Engineering](#business-analysis-and-bp-engineering)  
* [Business and Revenue Modelling](#business-and-revenue-modelling)
* [Operational reporting and BI](#operational-reporting-and-bi)
* [Data analysis and data hygiene](#data-analysis-and-data-hygiene) 

<br>Thank you for reading;)</br>

## Business Analysis and BP Engineering

#### 👉 BPMN example use for Appointment Settings process visualisation

__Goal:__ Provide a easy-to-read visual representation of the AS process for analysis, documenting and future reference e.g. in the new hire onboarding

__Skills:__ Business analysis, BPMN 2.0

__Results: [The BPMN top-level diagram for AS process](https://miro.com/app/board/uXjVNiNbKiI=/)__

#### 👉 Planning and designing the updated revenue process

__Goal:__ Plan, prepare and document a major update of the revenue process  

__Skills:__ Business analysis, process engineering, change and project management, requirement solicitation, revenue and sales KPI

__Results: [Global design document with example charts (detail redacted)](https://docs.google.com/document/d/1giJFaFxC3llHn1Sc5179GKAzNN8zob2pVR4KSCcrLL4/edit?usp=sharing)__

## Business and Revenue Modelling

#### 👉 One-pager revenue model for the sanity-check and forecasting

__Goal:__ Give the qualitative reality-check and project annual revenue given the lead channels composition, expected number of leads and the key conversion rates; identify the bottle necks and revenue sensitivities

__Skills:__ Business analysis, modelling, revenue and sales metrics, Google sheets

__Results: [The revenue model (redacted)](https://docs.google.com/spreadsheets/d/1YiU6LmTOVAg8TatVKFloPJm_9UbvCY93DYsBcNjTBmE/edit?gid=748648396#gid=748648396)__
   

## Operational reporting and BI

#### 👉 Ad-hoc analytics focused on the reps' performance and deal lost reasons

Once in a while you can spot an anomaly on the operating dashboards and need a quick dive into the specific area of the revenue flow. Data is clean and the basics tools would do the job fast.

__Goal:__ Assess the reps performance on the deals that take longer to close; get insights and support the decision making  

__Skills:__ Sales KPIs, descriptive statistics, pivot tables, data visualisation, analytical thinking

__Tech:__ Hubspot, Google sheets

__Results: [the report in pdf](https://github.com/outovhush/revops-data-portfolio/blob/main/Ad-hoc%20reports_AE%20WR%20lost%20deals%20quickstat_anon.pdf)__


## Data analysis and data hygiene

#### 👉 Data quality fast check

Suppose you have to combine manual data entry with a sort of custom data structure that is not fully supported by default in your database. Entry errors become likely. Validations and automated checks are hardly an option at this stage. Once in a while you'd need a reality check to see true extent of errors in the database. Full manual walk of the thousands of records is too expensive.
     
__Goal:__ Provide reliable estimate for the extent of data errors in the customer account database with the limited resources

__Steps:__
- figure out sample size given the CLT limitations for binomial
- set up the observations
- get the random sample
- check the sample manually collecting observations
- calculate sample means and confidence intervals

__Skills:__ Statistics (Binomial distribution, CLT), analytical thinking, Google sheets

__Results: [Google sheets report with the assessment](https://docs.google.com/spreadsheets/d/107Ku2k5vmR8ulyRyZNqTPoGAuRe9W2vTZqMGrSvtl5c/edit?gid=1064755575#gid=1064755575)__

#### 👉 CRM deal dataset exploration

__Goal:__  Explore raw CRM annual deal dataset, check some business metrics, identify inconsistencies and errors in the data

__Skills:__ Data cleaning, data exploration, Pearson correlation, data visualisation

__Tech:__ Python, Pandas, Matplotlib, Seaborn

__Code: [Example notebook_Deal dataset exploration.ipynb](https://github.com/outovhush/revops-data-portfolio/blob/main/Example%20notebook_Deal%20dataset%20exploration.ipynb)__

__Results:__ Few essential business metrics were visualised; the analysis revealed that expected correlations were not held for all lead generation channels. Major inconsistencies in the data were identified    

#### 👉 Critical data errors visualisation in CRM data

__Goal:__ Visualise error in the deal datapoint that is critical for correct deal stat; make it easy for further manual checks and corrections  

__Skills:__ Data cleaning, data analysis, data visualisation

__Tech:__ Python, Pandas, Matplotlib

__Code: [Example notebook_check deals source.ipynb](https://github.com/outovhush/revops-data-portfolio/blob/main/Example%20notebook_check%20deals%20source.ipynb)__

__Results: [image with clickable links in a standalone pdf](https://github.com/outovhush/revops-data-portfolio/blob/main/deal_source_plot_Create_date.pdf)__



