# m.c-squared-2


### Predicting Diabetes from CDC Annual Health Survey

### Background

Diabetes represents a significant challenge for the US healthcare system, with estimated costs reaching $412 billion annually. These figures encompass the immediate healthcare expenses associated with diabetes management but fall short of accounting for the extensive long-term costs tied to chronic conditions that may arise from poorly managed or undiagnosed diabetes. Recognizing the indirect health complications linked to diabetes is crucial, as it not only ranks as the 8th leading cause of death in the U.S., trailing closely behind Alzheimer’s disease, but also acts as a catalyst for other chronic health issues. Early detection of diabetes is a pivotal factor in enhancing long-term health outcomes and mitigating these extensive costs.

### Sources

* American Diabetes Association Economic Report

* National Center for Biotechnology Information


### Project Goals
1.	Develop a Predictive Model: Utilize existing health survey data to develop a model predicting the likelihood of an individual developing diabetes.
2.	Non-Invasive Assessment: Enable individuals to assess their diabetes risk without the need for a doctor's visit or bloodwork, using self-reported health information.
3.	Health Awareness: Increase health awareness through early-stage recommendations for a doctor's consultation if a high risk of diabetes is predicted.
4.	Improve Long-Term Health Outcomes: Aim at improving long-term health outcomes through the early detection of diabetes.

### Data Collection
Data was sourced from the responses to the 2015 Annual CDC Health Survey, comprising 400K respondents and 330 questions. Our selection process involved a detailed review of the 'Codebook 15' document, identifying relevant health questions for the diabetes prediction model. Additional insights were gained from an existing notebook by Alex Teboul on diabetes health indicators, which provided a preliminary list of predictive features. Our selection expanded upon these features, adapting the data cleanup process for our specific project needs.

### Data Preparation
Our data cleaning efforts resulted in a final dataset of approximately 208K respondents without diabetes, 4 in the pre-diabetic range, and 34 diagnosed with diabetes.

### Workflow
Our approach employed supervised learning models to align with the project's objectives, utilizing tools such as Scikit-learn, Matplotlib, Pandas, and Prophet. We evaluated several models, including Gradient Boosting Classifier, Random Forest Classifier, and Logistic Regression, on both multiclass and binary versions of our dataset. The Gradient Boosting Classifier emerged as the most effective model.

### Project Summary
#### Insights and Recommendations

Our analysis indicates that while the current dataset offers valuable insights, it is not sufficiently comprehensive for predicting diabetes with high accuracy. To enhance the model's predictive capabilities, we recommend:

* Detailed Follow-Up Questions: Implementing more nuanced follow-up questions for respondents exhibiting potential diabetes precursors, such as mobility issues.

* Prescreening Tool Potential: Despite its limitations, the model serves as an effective prescreening tool, encouraging individuals at risk to seek further medical evaluation through blood tests.

This project underscores the importance of early diabetes detection and the potential of using self-reported health information as a non-invasive assessment tool to prompt medical consultation, thereby contributing to better health outcomes.


### Credits

Our prject employed the work of Alex Teboul under the CC0 License as the foundation of our data cleaning process.