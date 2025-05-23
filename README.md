# Healthcare_payments

**Goal**
- Analysis of payments by gender to generate insights for understanding payment disparities. The insighste were generated to identfy gaps based on skills, activies performed that differentiated payments and payment modes.

**Data source**
- The analysis has been done on dataset published by OpenPaymentsData.CMS.gov with the aim to provide financial transparecncy within centers of medicare and medicaid services in United states. It comproses of ayments made by healthcare companies to various stake holders like research organizations involved in drug discovery, teaching hospitals, physicians and non-physicians involved in clinical trials. The payments are made by pharmaceuticals, medical device manufacturers, GPO group purchase organizations, the distributors of drugs, medicla and biological supplies. The data is published evey year. This analysis is for year 2023. The general and research payment datasets were analyzed. https://openpaymentsdata.cms.gov/datasets

**Scope**
- The analysis is deterministic and statistical methods have been used to explore and compare payments types, roles and specialities of physicians and non-physicians. There is special focus on gender based analysis, to identify geneder based payment disparity and differences in the roles, activities and mode of payments.

**Dataset processing**
- The real life datasets are very large and require lot of cleaning, preparation and segmentation. To uphold privacy of indiviuals, the PII information was removed and only gender and ID of individuals were used.
- General payments and research payments were analyzed. The general payments was 
- The dataset comprised of hundreds of organizations. Only top 20 organiations were considered.
- The analysis was done is stages. EDA was performed. A master dataset was created. A broad level analysis was done across entire industry.
- Data was segmented for only pharmaceutical company for analysis.
- Data was further filtered by organizations and their subsidiaries and analyzed.

**Outcomes**
- Healthcare is a biggest employer in United states. The gender based disparity is minimum. At broad level the gender ratio was balanced. However the data insights revealed that there were more female employees in non-physian roles 70-75% and at physician and research roles on average 30%.
- In research females were equally competent in skills and there was payment parity. However workforce comprised 30% only. 
- In general payments, across physicians the payments were skewed. Males travelled more, were speakers at educational events, earned more on royalties and licenses, in travel and lodging, food and beverages. They were paid in cash while women were paid more in kind items and services.
- Non-Physian roles were broadly analyzed, without considering skills. There was in general parity. Though varied across organizations.

**Challanges**
- Entire analysis is based on the dataset.
- The data was reported by organizations and we are not aware if it is incomplete.
- The gender was predicted using names of individuals. The precision was 83%.
  
