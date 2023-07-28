# Case-Marketing-RFM-Dashboard
The data, content, and final delivery I shared on GitHub utilize mock-up data due to confidentiality.The main goal of this project is to demonstrate my expertise in data analysis, modeling, and problem-solving.

## Table of Contents

1. [Introduction](#introduction)
2. [Specifications](#specifications)
3. [RFM Dashboard Proof of Concept](#rfm-dashboard-proof-of-concept)
4. [Dataset](#dataset)
5. [Model Simulation](#model-simulation)
6. [Results](#results)
    - [Proof of Concept Dashboard Design](#proof-of-concept-dashboard-design)
    - [Dashboard Highlights](#dashboard-highlights)
7. [Lessons Learned](#lessons-learned)

---

## 1. Introduction <a name="introduction"></a>

XYZ Bank is a prominent financial institution with over 1000 branches spread across Canada. The bank's management aims to gain insights into customer loyalty and their sales contributions through RFM methodology-based segmentation. They seek a robust, long-term production solution to assist the Business-CRM Services department in enhancing profitability and increasing customer loyalty. This solution will involve conducting an analysis using the recency, frequency, and monetary (RFM) methodology to segment customers, allowing for targeted Campaign Planning & Design based on the results.

## 2. Specifications <a name="specifications"></a>

- **Name**: XYZ CRM RFM Analysis Dashboard BRD, Dashboard design spec, data model
- **Description**: XYZ Customer contribution based on RFM methodology to identify target customers for future campaign planning and implementation.
- **Language(s)**: English
- **Owners/Requester**: XYZ management
- **Audience**: Business – CRM Department
- **Security Parameters**: ALL Executives

## 3. RFM Dashboard Lifecycle <a name="rfm-dashboard-proof-of-concept"></a>
<img width="805" alt="238653169-83047e77-a0b1-4bf5-95cc-ed5a4f3e461a" src="https://github.com/connieyeee/Case-Marketing-CRM-RFM-Dashboard/assets/134975561/c06df641-03a7-41e6-8471-b52d7b76cd15">

## 4. Dataset <a name="dataset"></a>
The analysis incorporates five datasets, comprising of three source data and two data mart data. Besides, to identify the target customers and their sales contribution by segment, the analysis will exclude transactions related to transfers, taxes, bills and utilities, mortgage and rent.

#### Source Data:
*BusinessCase_Accts*: This dataset contains comprehensive information about accounts, including branch number, type, open date, ID, balance, currency, and customer ID.

*BusinessCase_Custs*: This dataset provides customer-related details such as ID, gender, birth date, work activity, occupation, total income, habitation status, and school attendance.

*BusinessCase_Tx*: This dataset plays a significant role throughout the analysis and includes information on transaction descriptions, currency amounts, origination date-time, customer ID, merchant ID, account ID, and category tags. The transactions occurred between March 1, 2018, and November 1, 2018.


#### Target Data:
*RFM SCORE*: This dataset represents the filtered and calculated values derived from the original transaction data using the RFM methodology. It includes columns for customer ID, recent purchase date, monetary value, and frequency.

*Segmentations*: This dataset is designed to assign names and descriptions to each segment based on different R-F-M scores. It provides information on the R-F-M score, segment name, description, and sorting.

## 5. Model Simulation <a name="model-simulation"></a>
![Picture1](https://github.com/connieyeee/Case-Marketing-CRM-RFM-Dashboard/assets/134975561/2c23b381-6b70-4661-b2b9-34a8221dc7b5)

## 6. Results <a name="results"></a>
Proof of Concept Dashboard Design:<a name="proof-of-concept-dashboard-design"></a>
![RFM Dashboard](https://github.com/connieyeee/Case-Marketing-CRM-RFM-Dashboard/assets/134975561/d84b9377-c86c-46cc-9ea7-5bcc1fb17172)


