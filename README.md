# Sampling_Assignment
This is in accordance with the given assignment: https://github.com/AnjulaMehto/Sampling_Assignment

In this python code, we have used sampling techniques on a credit card fraud detection dataset 
and then applied various ML models on the dataset to find out which Model,sampling technique combination
gives us the best accuracy.

Sampling
This program is designed to download a credit card fraud detection dataset and apply various sampling techniques to create a balanced dataset. The balanced dataset is then used to create five samples and apply five different sampling techniques to five machine learning models.

Data Source:
The credit card fraud detection dataset is available at the following link: https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv

Requirements:
To run this program, the following packages need to be installed:
•pandas
•imblearn
•scikit-learn

The sampling techniques used in this program are:
1.Random Under Sampler (Sampling1)
2.Random Over Sampler (Sampling2)
3.SMOTE (Sampling3)
4.TOMEK links (Sampling4)
5.Near Miss (Sampling5)

The five machine learning models used in this program are:
1.Logistic Regression (M1)
2.Decision Tree Classifier (M2)
3.Random Forest Classifier (M3)
4.Support Vector Classifier (SVC) (M4)
5.Extra Tree Classifier (M5)

The Sample size was calculates using the following formula: n = Z^2(p(1 – p)/m^2) where: n = sample size Z = z-value (for 99% confidence interval, Z = 2.576) p = proportion of the minority class (taken as 0.5 for a balanced dataset) m = margin of error (taken as 0.05 for a sample size of 1000)

On execution of the code, following results were obtained:

https://raw.githubusercontent.com/kish-crack/Sampling_Assignment/main/Output.png


