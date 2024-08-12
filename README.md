# Synthetic Healthcare Dataset

## About the Dataset

### Context
This synthetic healthcare dataset has been created as a valuable resource for data science, machine learning, and data analysis enthusiasts. It is designed to mimic real-world healthcare data, allowing users to practice, develop, and showcase their data manipulation and analysis skills in the context of the healthcare industry.

### Inspiration
The inspiration behind this dataset stems from the need for practical and diverse healthcare data for educational and research purposes. Healthcare data is often sensitive and subject to privacy regulations, making it difficult to access for learning and experimentation. To address this challenge, I used Python's Faker library to generate a dataset that mirrors the structure and attributes commonly found in healthcare records. By providing this synthetic data, I aim to foster innovation, learning, and knowledge sharing in the healthcare analytics domain.

## Dataset Information

The dataset consists of various columns, each providing specific information about the patient, their admission, and the healthcare services provided. This dataset is suitable for various data analysis and modeling tasks in the healthcare domain. Below is a brief explanation of each column in the dataset:

- **Name:** The name of the patient associated with the healthcare record.
- **Age:** The age of the patient at the time of admission, expressed in years.
- **Gender:** Indicates the gender of the patient, either "Male" or "Female."
- **Blood Type:** The patient's blood type, which can be one of the common blood types (e.g., "A+", "O-", etc.).
- **Medical Condition:** The primary medical condition or diagnosis associated with the patient, such as "Diabetes," "Hypertension," "Asthma," and more.
- **Date of Admission:** The date on which the patient was admitted to the healthcare facility.
- **Doctor:** The name of the doctor responsible for the patient's care during their admission.
- **Hospital:** Identifies the healthcare facility or hospital where the patient was admitted.
- **Insurance Provider:** Indicates the patient's insurance provider, which can be one of several options, including "Aetna," "Blue Cross," "Cigna," "UnitedHealthcare," and "Medicare."
- **Billing Amount:** The amount of money billed for the patient's healthcare services during their admission, expressed as a floating-point number.
- **Room Number:** The room number where the patient was accommodated during their admission.
- **Admission Type:** Specifies the type of admission, which can be "Emergency," "Elective," or "Urgent," reflecting the circumstances of the admission.
- **Discharge Date:** The date on which the patient was discharged from the healthcare facility, based on the admission date and a random number of days within a realistic range.
- **Medication:** Identifies a medication prescribed or administered to the patient during their admission. Examples include "Aspirin," "Ibuprofen," "Penicillin," "Paracetamol," and "Lipitor."
- **Test Results:** Describes the results of a medical test conducted during the patient's admission. Possible values include "Normal," "Abnormal," or "Inconclusive," indicating the outcome of the test.

## Usage Scenarios

This dataset can be utilized for a wide range of purposes, including:

- Developing and testing healthcare predictive models.
- Practicing data cleaning, transformation, and analysis techniques.
- Creating data visualizations to gain insights into healthcare trends.
- Learning and teaching data science and machine learning concepts in a healthcare context.

### Multi-Class Classification Task

You can treat this dataset as a Multi-Class Classification Problem and solve it for the **Test Results** column, which contains three categories: "Normal," "Abnormal," and "Inconclusive."

## Included Notebooks

Two Jupyter notebooks are included in this repository:

1. **Data Analysis Notebook (`data_analysis.ipynb`)**: This notebook provides an exploratory data analysis of the synthetic healthcare dataset. It includes data cleaning, transformation, and visualization techniques to gain insights into the dataset.

2. **Healthcare Classification Notebook (`healthcare_classification.ipynb`)**: This notebook demonstrates the process of building classification models to predict the test results using various classification algorithms. It includes model training, evaluation, and comparison of different models.

## Acknowledgments

I acknowledge the importance of healthcare data privacy and security and emphasize that this dataset is entirely synthetic. It does not contain any real patient information or violate any privacy regulations.

I hope that this dataset contributes to the advancement of data science and healthcare analytics and inspires new ideas. Feel free to explore, analyze, and share your findings.
