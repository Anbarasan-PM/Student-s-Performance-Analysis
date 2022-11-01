# Student's-Performance-Analysis
Why ?
The economic success of any country depends on making higher education more affordable and that is one of the main concerns for any government. One of the factors that contributes to the educational expenses is the studying time spent by students. Machine learning techniques can be used to predict the performance of the students and identify the at-risk students as early as possible. This research examines how student’s health is affected by various factors such as time spent on social networks etc and predicting G3 by considering some other factors such as G1 and G2. Random Forest and Linear Regression techniques have been used to build the machine learning model. The dataset was data was obtained in a survey of students' math course in secondary school during the year 2019-2020.
Required Libraries :
                 pandas, numpy, seaborn, matplotlib, sklearn, tkinter.
Steps:
     -> First EDA(Exploratory Data Analysis) is performed to get insights from the dataset.
     -> Finding the unnecessary features from the insights that will be required for furthur analysis.
     -> . Random Foredt Regressor :- This algorithm is used here for the classification purposes.It performs good to this suitation because it gives result based on                                        the majority voting.Here random forest regressor is used to calssify the students based on the health say(1-Good,2-Moderate,etc)
        . Multi Linear Regression :- The basic idea behind regression is to find the pattern from the data and used for predicting the future values based on the                                            input given.Here multi linear regression is used to predict the marks of the student's (G3)final exam based on the exam marks of                                        (G1,G2)previous exams.
Conclusion:
         If the studemt's health is less than 3 say(1 - good, 2 - moderate) they are performing good in exams.
