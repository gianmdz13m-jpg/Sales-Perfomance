# Data Cleaning and Preparation

The first step was to identify and understand the key metrics in order to prioritize which columns required cleaning. The primary metric is USD_PRICE, as it represents the core financial value of the dataset. This is followed by PURCHASE_TS, which serves as the time dimension, and PRODUCT_NAME, MARKETING_CHANNEL, and COUNTRY_CODE, which provide important contextual dimensions.

The next step involved reviewing each column for potential issues, specifically checking for inconsistent data formats, inconsistent categorizations, null values, outliers, business logic violations, and duplicate records.

The final step consisted of resolving the identified issues using Power Query. However, errors requiring a source of truth, such as duplicated order IDs or missing transactional records, were documented but left unchanged, as they could not be reliably corrected within the dataset itself.

The table below summarizes the issues identified and the corresponding resolutions applied.

![Data](/img/Data_Cleaning.png)
