# Predict Student Achievement Using Virtual Learning Environment Log Data

This is my Bachelor's Project in Computing Science, at the University of Groningen. The project was supervised by Prof. Dr. Asadollah Shahbahrami (University of Groningen) and Prof. Dr. Carlo Galuzzi (Delft University of Technology).

## Abstract

Using virtual learning environments (VLE) in tertiary education gave new opportunities to researchers from the Educational Data Mining field. Predictive analytics is a sub-group that can solve problems that affect the students, such as extended duration to finish a degree. Using 3 machine learning algorithms, we analyse which are the aspects that impact student achievement. On the other hand, we predict if a student will pass or fail a course, from the midpoint of the module. The Open University Learning Analytics (OULA) [(dataset link)](https://analyse.kmi.open.ac.uk/open_dataset) dataset was used, creating a set of features that applies to all the courses from this data collection. The independent variables are categorised into 3 groups, these being demographics, assessments and VLE interactions. In both experiments, the best results were obtained using Random Forest (RF) and Light Gradient-Boosting Machine. We conclude that when predicting future achievement, the most impactful component is the past results of the student. Furthermore, we obtained an 88.88 Area Under the Curve, using RF, when predicting the student performance, while using data from the first half of the course.

### Comparisons
For research question 1 we obtained better results than one paper and worse than 2 others that use the OULA dataset. On the other hand, the current literature review does not contain similar papers for research question 2 that use the OULA dataset. Compared with other papers, that use a different dataset, we obtained worse results. 

### How to use
Due to its size, the OULA dataset can't be uploaded on GitHub. Download the tables from [here](https://analyse.kmi.open.ac.uk/open_dataset), create in the root folder a folder called 'OULAD_dataset' and move the tables there. The project is made to work in a local environment, so if you want to use the notebooks in an environment such as Google Colab, you will have to make some changes.

### Project Structure
In the "FeatureImportance" folder, there is the process for research question 1, which states "Which factors have an impact on a student’s achievement?". There is present the Q1_Final_dataset_dev which presents the creation of the features and the final dataset used in the research. Then in "Models", there are the 3 algorithms that were used in the analysis, each notebook having also the feature importance for each model. 

In the "50%PassFailPrediction" folder, there is the process for research question 2, which states "Is it possible to predict student achievement at the midpoint of a course?". There is present the Q2_Final_dataset_dev which presents the creation of the features and the final dataset used in the research. Then in "Models", there are the 3 algorithms that were used in the analysis.