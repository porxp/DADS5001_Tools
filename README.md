Created by Thatchaphan Samphansompoch 6610422012
This on of assignment in DADS5001 Tools 

   This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. 
The objective of the dataset is to diagnostically predict a patient has diabetes.
Data source:https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset/data

Information about dataset attributes:
Pregnancies: To express the Number of pregnancies
Glucose: To express the Glucose level in blood
BloodPressure: To express the Blood pressure measurement
SkinThickness: To express the thickness of the skin
Insulin: To express the Insulin level in blood
BMI: To express the Body mass index
DiabetesPedigreeFunction: To express the Diabetes percentage
Age: To express the age
Outcome: To express the final result 1 is Yes and 0 is No

Using the heatmap correlation 
   The heatmap correlation shows the relationship between different variables in the diabetes dataset. 
The color of each cell in the heatmap indicates the strength and direction of the correlation between 
the variables represented by the row and column headers.

This is the heatmap correlation from data.
![AS03_tools](https://github.com/porxp/DADS5001_Tools/assets/158511035/90b58336-0737-4d09-bce2-625c99973e08)

To interpret the graph:
Based on the heatmap correlation, we can observe that some variables have a strong positive correlation 
with the target variable (Outcome), such as Glucose and BMI. This suggests that higher values of these 
variables are associated with a higher likelihood of having diabetes. On the other hand, some variables 
have a weak or no correlation with the target variable, such as BloodPressure, Insulin and SkinThickness.

It is important to note that correlation does not imply causation, and further analysis is needed to 
determine the causal relationships between variables. However, the heatmap correlation provides a useful 
starting point for exploring the relationships between variables in the dataset.
