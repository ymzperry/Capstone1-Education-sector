# Capstone1-Education-sector
The purpose of this capstone project is to use machine learning to monitor students’ academic progress and provide timely assistance to those who are very likely to fail the final exam based on the model prediction.  

The factors that used in the dataset to predict future academic performance include students’ gender (even marriage status if for female), the campus locations (i.e., in response to the different enrollment requirement), class type (i.e., daytime or evening part-time class: a surrogate of time management), three in-semester assignments (i.e., a proxy for their progressing academic record), and the final exam score. 

I used the seen data that included historical in-semester scores as well as the released final score to sort into the model. The information was in the year 2020 which has been factored the adverse impact of the pandemic on distance learning. Thus, it shall be consistently applied at least in the upcoming one to two years. I used algorithms such as LogisticRegression, RandomForestRegression, and GradientBoostedRegression, with tuning key hyperparameters based on simulated pre-analysis. 

The best AUROC score (predicted v. actual) by functional departments from pipelines cross-validation is 73%+.

I use the model established by seen data to predict unseen data in a new teaching semester. 

Limitations (or further advice) on this project: given the predicted outcome is a categoried type variable (i.e., fail, pass, distinction, higher distinction), I am thinking would be any improvement to make the predicted outcome more accurate that close to the specific score (i.e., continuous variable but not categoried type)? 
