[TehSongXuan_Personal_Loan_AIMLProject2_full_code - Copy.html](https://github.com/user-attachments/files/25361473/TehSongXuan_Personal_Loan_AIMLProject2_full_code.-.Copy.html)
# personal-loan-risk-analytics
Personal loan analytics project applying machine learning and data visualisation to generate actionable insights for customer targeting and innovation strategy. Includes executive-ready presentation, model evaluation, and business recommendations to support data-driven decision-making and digital solution adoption in a banking context.
# ReneWind Predictive Maintenance ML Case Study

Failure prediction for wind turbine generators using sensor data, neural network modelling, and recall-focused optimisation.

## Project Overview
This project analyses a predictive maintenance use case for ReneWind, a wind energy company seeking to identify generator failures before breakdown.

The analysis focuses on translating machine learning outputs into operational decision-making, including earlier failure detection, reduced maintenance costs, and improved asset reliability.

Beyond modelling, this case study demonstrates how analytics can be structured into clear, decision-ready insights for business stakeholders.

## Business Problem
ReneWind aims to reduce generator downtime and maintenance costs by predicting failures in advance.

In this problem:
- True Positives (TP): failures correctly predicted → repair costs
- False Negatives (FN): failures missed → higher replacement costs
- False Positives (FP): normal cases flagged → inspection costs

Because missed failures are more costly than false alarms, **Recall** is prioritised as the key evaluation metric.

## Objective
Build and compare classification models to:
- identify likely generator failures early
- support preventive maintenance decisions
- reduce operational risk and downtime

## Dataset
- 40 predictor variables  
- 20,000 training observations  
- 5,000 test observations  

Target variable:
- `1` = failure  
- `0` = no failure  

The dataset is a transformed version of confidential sensor data.

## Approach
The project follows a structured machine learning workflow:

1. Business understanding and problem framing  
2. Exploratory data analysis  
3. Data preprocessing  
4. Baseline neural network modelling  
5. Model improvement through experimentation  
6. Model evaluation using recall, precision, F1-score, and confusion matrices  
7. Translation into business insights  

## Model Development
Multiple neural network configurations were developed and compared, including:
- baseline model  
- dropout regularisation  
- class-weighted model for imbalanced data  
- SGD vs Adam optimisers  
- deeper architectures with additional hidden layers  

The focus was on improving recall while maintaining generalisation performance.

## Key Results
- Model 3 achieved the strongest recall performance on unseen data  
- Demonstrated that accuracy alone is not suitable for imbalanced predictive maintenance problems  
- Highlighted trade-offs between higher recall and lower precision  
- Reinforced the importance of aligning model selection with business risk  

## Business Insights
This project demonstrates how machine learning can support operations by:
- detecting failures earlier  
- reducing unplanned downtime  
- prioritising maintenance actions  
- improving asset reliability  
- enabling proactive maintenance strategies  

## Strategic Relevance
This case study reflects how analytics capabilities can be translated into broader operational and innovation contexts:

- supports integration into predictive maintenance systems  
- enables data-driven decision frameworks for operations teams  
- demonstrates how models can evolve into scalable solutions  
- highlights the importance of aligning technical outputs with business priorities  

## Files in this Repository
- `README.md` — project overview and summary  
- `TehSongXuan_INN_ReneWind_Project_FullCode.html` — full notebook  
- `images/` — charts and model outputs  
- `docs/` — optional GitHub Pages version  

## View the Full Project
[View ReneWind Full Project](https://github.com/user-attachments/files/XXXXXXXX/TehSongXuan_INN_ReneWind_Project_FullCode.html)

## Tools Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib / Seaborn  

## Why This Project Matters
This case study reflects my focus on:
- translating machine learning into business value  
- structuring insights for stakeholder understanding  
- bridging technical analysis with operational outcomes  

## Future Enhancements
- explore tree-based ensemble models  
- implement cost-sensitive threshold tuning  
- design deployment-ready alert systems  
- integrate outputs into dashboards or reporting tools  

## Author
Song Xuan
