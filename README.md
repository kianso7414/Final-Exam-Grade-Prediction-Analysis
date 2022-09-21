# Final-Exam-Grade-Prediction-Analysis
This is a self-learning project using test score data to predict student's final exam grade.

The data is provided by HKUST, information contains final exam's 'scaled_score', the 'Topic' scores from test1/test2 and 563 'question' score.
All analysis is done to enhance the accuracy for predicting student's final exam grade.

The machine learning model is built using logistic regression using only 2500 data points, with only 'Topics' features introduced, with hyperparameter tuned by using Flaml AutoML and EvalML.


Model result in ~35% accuracy in predict their grade, and ~75% accurcy within one sub grade deviation from the prediction.


With the learning curve studied, we see the increasing amount of data may bring limited benefit to the model. However, it can be considered to include more features to better categorized student's grade.

The model is premitive and has high potential considered that students only do 20 questions out of 563, which only contains the content from the first half of the semester. With more features included, 50% accuracy for prediction and >90% accuracy of prediction fall within one sub grade deviation can be desired.
