# HEALTHCARE PROVIDER FRAUD DETECTION ANALYSIS
## Dataset Source
### From Website
[Dataset](https://www.kaggle.com/code/rajesh2609/medicare-provider-fraud-detection)

[Dataset Helper](https://www.kaggle.com/datasets/rajesh2609/medicare-prv-fraud-files)
### Use Kaggle API
#### Install Kaggle API
```bash
pip install kaggle
```
#### Download Kaggle API Token
```bash
kaggle datasets download -d rohitrox/healthcare-provider-fraud-detection-analysis
kaggle datasets download -d rajesh2609/medicare-prv-fraud-files
```

## About Dataset
### Project Objectives
Provider Fraud is one of the biggest problems facing Medicare. According to the government, the total Medicare spending increased exponentially due to frauds in Medicare claims. Healthcare fraud is an organized crime which involves peers of providers, physicians, beneficiaries acting together to make fraud claims.

Rigorous analysis of Medicare data has yielded many physicians who indulge in fraud. They adopt ways in which an ambiguous diagnosis code is used to adopt costliest procedures and drugs. Insurance companies are the most vulnerable institutions impacted due to these bad practices. Due to this reason, insurance companies increased their insurance premiums and as result healthcare is becoming costly matter day by day.

Healthcare fraud and abuse take many forms. Some of the most common types of frauds by providers are:

- Billing for services that were not provided.
- Duplicate submission of a claim for the same service.
- Misrepresenting the service provided.
- Charging for a more complex or expensive service than was actually provided.
- Billing for a covered service when the service actually provided was not covered.

### Problem Statement
The goal of this project is to " predict the potentially fraudulent providers " based on the claims filed by them.along with this, we will also discover important variables helpful in detecting the behaviour of potentially fraud providers. further, we will study fraudulent patterns in the provider's claims to understand the future behaviour of providers.

Introduction to the Dataset
For the purpose of this project, we are considering Inpatient claims, Outpatient claims and Beneficiary details of each provider. Lets s see their details :

#### Inpatient Data

This data provides insights about the claims filed for those patients who are admitted in the hospitals. It also provides additional details like their admission and discharge dates and admit d diagnosis code.

#### Outpatient Data

This data provides details about the claims filed for those patients who visit hospitals and not admitted in it.

#### Beneficiary Details Data

This data contains beneficiary KYC details like health conditions,regioregion they belong to etc.