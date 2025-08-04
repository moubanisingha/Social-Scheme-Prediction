# 🧓 NSAP Scheme Eligibility Prediction

## 📌 Problem Statement

> The National Social Assistance Programme (NSAP) serves elderly, widowed, and disabled individuals from BPL households.  
> Matching applicants to the correct scheme is error-prone and manual.  
> This project automates eligibility prediction using demographic and socio-economic data which will help to optimize that    process and accurate delivery of financial aid to the eligible beneficiaries.

## 🛠️ Technologies Used

| 🧠 IBM AutoAI | Model training and optimization |
| ☁️ Watson Machine Learning | Deployment |
|🧪 Watson Studio	| Notebook development and workflow orchestration |
|🧬 IBM Watsonx.ai Runtime (Lite Plan) |	Runtime environment for model scoring and deployment |
|☁️ IBM Cloud Object Storage (Lite) | 	Dataset and model artifact storage |
| 📊 pandas, numpy | Data preprocessing |
| 📈 scikit-learn, seaborn | Evaluation & plots |
| 🧪 Jupyter Notebook | End-to-end experimentation |

## 📊 Solution Overview

This is a multi-class classification model trained using IBM AutoAI to predict the appropriate NSAP scheme (IGNOAPS, IGNWPS, IGNDPS) for a BPL applicant based on socio-economic and demographic inputs like age, gender, marital status, disability status, and income.

## 🚀 How to Use the Project

git clone https://github.com/moubanisingha/Social-Scheme_Prediction.git
cd Social-Scheme_Prediction
pip install -r requirements.txt
jupyter notebook "NSAP Scheme.ipynb"

## 📈 Results 

>Accuracy --> 98.4%
>Best Model -->	Batched Tree Ensemble Classifier

## 🌱 Future Scope

>Deploy as a web app using Streamlit
>Add real-time Aadhaar API integration
>Build multilingual UI for rural areas
>Integrate WhatsApp chatbot for accessibility

## 📎 Resources & References

> IBM AutoAI Documentation
> Dataset :  https://aikosh.indiaai.gov.in/web/datasets/details/district_wise_pension_data_under_the_national_social_assistance_programme_nsap_1.html




