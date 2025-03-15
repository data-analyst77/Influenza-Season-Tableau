# Influenza in the US 

## Research Context
The United States has an influenza season where more people than usual
suffer from the flu. Some people, particularly those in vulnerable populations, develop serious
complications and end up in the hospital. Hospitals and clinics need additional staff to
adequately treat these extra patients. The medical staﬃng agency provides this temporary
staff. Influenza deaths pose a challenge to the US healthcare system. Especially the vulnerable population aged 65+ is at risk.

## Project Objectives 
Objective: Determine when to send staff, and how many, to each state.
Scope: The agency covers all hospitals in each of the 50 states of the United States, and
the project will plan for the upcoming influenza season.

Relevant stakeholders: Medical agency frontline staff (nurses, physician assistants, and doctors)
● Hospitals and clinics using the staﬃng agency’s services
● Influenza patients
● Staﬃng agency administrators

## Guiding Questions
1.	Is there evidence to support the common assumption of a positive linear relationship between BMI, age, smoking, and healthcare costs?
2.	How do health variables (such as smoking and BMI) differ between genders? Do these differences also translate into varying healthcare charges by gender?
3.	How is obesity (BMI) related to smoking? Is there a positive linear relationship between the two?
4.	What types of regional differences can be detected in healthcare costs and health factors?

## Data 
**Kindly note the '02_Data' file was not uploaded due to storage space**.  

**Data Description**
- US Census Bureau Data: Population data & age distribution
- CDC Data set: Influenza deaths by state
- CDC Data set: Survey of flu shot rates in
children

**Data Wrangling & Cleaning** 
-	Data was checked for missing values, duplicates, mixed-type data, and correct data type. No deviations were found. 
- state: To approximate **state-level data**, a new column was added by randomly assigning states within their ([CDC-defined regions](https://www2.census.gov/geo/pdfs/maps-data/maps/reference/us_regdiv.pdf)). While this preserves broad regional trends, it does not reflect **state-specific healthcare policies, costs, or demographics**, making **state-level comparisons unreliable**.

**Methods** 
Data cleaning, integration,
transformation; hypothesis testing; visualisation. 

**Further Data Analysis Results** 
The script gives detailed insight into conducted analysis, a more visual presentation was compiled on Tableau, available ([here on Tableau Public](https://public.tableau.com/views/Dashboard_US_Healthcharges_DA77/USHealthcareCharges?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))

## Limitations  
This dataset is **synthetic** and lacks a defined timeframe, limiting its reliability for real-world policy decisions. Insights should be interpreted cautiously, as potential biases in data generation may lead to misleading conclusions without validation against real-world data.  

- **BMI** is an oversimplified health indicator, as it does not account for body composition or physical fitness.  
- **Smoking status** is represented as a binary variable, which does not capture smoking frequency or intensity but serves as a simplified measure for analysis.  

## Ethical Considerations 
- While the dataset does not contain personally identifiable information (PII), there remains a risk of **bias** that could contribute to **discrimination** in insurance pricing or policy decisions. Health insurers must ensure that predictive models do not disproportionately impact vulnerable populations or reinforce existing disparities. Transparency in data use and adherence to ethical AI practices are critical to maintaining fairness and public trust in insurance decision-making.  
- Considering the limitations of the **BMI** and **smoking** variables, health insurance providers should treat this information with caution, recognizing that both variables are **oversimplified** and may not fully reflect the complexity of individual health factors.
