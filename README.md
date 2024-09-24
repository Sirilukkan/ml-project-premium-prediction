# ML Project: Health Insurance Premium Prediction

**Codebasics ML Course Health Insurance Prediction Project**

## Project Overview:
This project aims to develop a predictive model for Shield Insurance to estimate annual health insurance premium amounts based on several factors, including age, smoking habits, BMI, and medical history. The project also involves building and deploying a predictive model using a Streamlit application.

### Data Description:
| Column                | Description                                                                                             |
|-----------------------|---------------------------------------------------------------------------------------------------------|
| Age                   | The age of the insured person, typically in years.                                                      |
| Gender                | The gender of the insured person, typically categorized as 'Male', 'Female', or 'Other'.                 |
| Region                | The geographical area where the insured person resides. This can influence risk factors and premiums.    |
| Marital Status        | The marital status of the insured person, such as 'Single', 'Married', 'Divorced', or 'Widowed'.         |
| Number of Dependants   | The number of dependants the insured person has, which can affect the insurance coverage and premium.    |
| BMI Category          | The body mass index (BMI) category of the insured person (e.g., Underweight, Normal, Overweight, Obese). |
| Smoking Status        | Whether the insured person is a smoker ('Yes' or 'No'), as smoking impacts health risks and premiums.    |
| Employment Status     | The current employment status of the insured person (e.g., Employed, Unemployed, Retired).              |
| Income Level          | The income level of the insured person, categorized by ranges (e.g., Low, Medium, High).                |
| Income (in Lakhs)     | The annual income of the insured person, represented in lakhs (a unit in the Indian numbering system).   |
| Medical History       | The past and present medical conditions of the insured person, which can affect eligibility and premiums.|
| Insurance Plan        | The type of insurance plan selected by the insured person (e.g., Basic, Premium, Comprehensive).        |
| Annual Premium Amount | The amount paid by the insured person for the health insurance policy on an annual basis.                |

## Building ML Models:
Check out the [Experimentation](https://github.com/Sirilukkan/ml-project-premium-prediction/tree/main/Experimentation) section for data cleaning, preprocessing, and machine learning model building.
## Model Accuracy:
* XGBoost Regressor model with > 97% accuracy and < 10% error between predicted and actual premium amount.


## Building Apps:
![App Screenshot](https://github.com/user-attachments/assets/da91e49c-0e01-4404-a366-04a5490445f8)

- The `artifacts` contains models and a scaler for two age groups: <= 25 and > 25.

## Deploying the Application:
You can access the deployed application here: [Streamlit App](https://ml-project-premium-prediction.streamlit.app/)


