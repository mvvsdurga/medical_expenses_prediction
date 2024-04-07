Medical-Expenses-Prediction
Project Summary
Everyone’s life revolves around their health. Good health is essential to all aspects of our lives. Health refers to a person’s ability to cope up with the environment on a physical, emotional, mental, and social level. Because of the quick speed of our lives, we are adopting many habits that are harming our health. One spends a lot of money to be healthy by participating in physical activities or having frequent health check-ups to avoid being unfit and get rid of health disorders. When we become ill, we tend to spend a lot of money, resulting in a lot of medical expenses. So, an application can be made which can make people understand the factors which are making them unfit, and creating a lot of medical expenses, and it could identify and estimate medical expense if someone has such factors.

Project description:
This project aims at building Machine Learning models which can predict a patient's medical expenses based on specific features Factors affecting the medical expenses of the patients :
• Age
• Gender
• Body Mass Index
• Region
• Smoking Behavior

Business Implications of the Project:
• Health is the center of everyone’s life.
• Every part of our life relies on good health.
• Health is the extent of an individual’s continuing physical, emotional, mental, and social ability to cope with the environment.

This project helps in identifying the factors affecting the medical expenses of the subjects based on the model output.

Data Source:
• The dataset has been sourced from kaggle.com and on GitHub.
• This data file includes all needed information to find out more about age, gender, smoking behavior and necessary metrics to make predictions and draw conclusions.
• Link to the dataset: https://github.com/stedy/Machine-Learning-with-R- datasets/blob/master/insurance.csv

The dataset contains information on 1,338 patients. It includes the following features:
• Age: Patient's age
• Sex: Patient's sex
• BMI: Patient's Body Mass Index
• Children: How many children the patient has
• Smoker: Whether the patient is a smoker or not
• Region: Which region the patient is from (Northeast, Southeast, Southwest, Northwest)
• Expenses: Individual medical costs billed by health insurance

Target Variable:
The Expenses column is the target column, and the rest others are independent columns. Independent columns are those which will predict the outcome.

Independent Variables:
The first column is Age. Age is an important factor for predicting medical expenses because young people are generally more healthy than old ones and the medical expenses for Young People will be quite less as compared to old people.

The Next column is sex, which has two Categories in this column: Male and Female. The sex of the person can also play a vital role in predicting the medical expenses of a subject.

After that, you have the ‘bmi’ column, then BMI is Body Mass Index. For most adults, an ideal BMI is in the 18.5 to 24.9 range. For children and young people aged 2 to 18, the BMI calculation considers age and gender as well as height and weight. If your BMI is less than 18.5, you are considered underweight. People with very low or very high ‘bmi’ are more likely to require medical assistance, resulting in higher costs.

The fourth column is the ‘children’ column, which contains information on how many children your patients have. Persons who have children are under more pressure because of their children’s education, and other needs than people who do not have children.

The fifth is the ‘smoker’ column. The Smoking factor is also considered to be one of the Most Important factors as the people who smoke are always at risk when their age reaches 50 to 60.

Next is the ‘region’ column. Some Regions are Hygienic, Clean, Neat, and Prosperous, But some Regions are not, and this information affects health which is related to medical expenses.

Steps:

• Data Pre-Processing
• Exploratory Data Analysis : Data Visualization, Univariate Analysis and Data Processing
• Data Modelling
• Evaluation
• Conclusion
• Recommendations
• Future Work

Evaluation:
• We came to know that the Most Important Factor to Predict the Medical Expenses of a subject is Smoking Behavior and Age, that means, smoking is Bad for Health, as we already know that and which inevitably increases medical expenses as due to smoking one is likely to fall ill more than the nonsmokers.


• We also found that with increasing of age, one needs to take some more care and precautions for your health as with the increase of age health becomes fragile, so they go for frequent medical check-up, likely to fall ill quickly as with the increase of age immunity falls so they adopt measures to stay healthy by taking medicines and engaging in some physical activities.


• Apart from that we also understood that Gender, Number of Children, the Region also have a good impact on determining Medical Expenses.

Conclusion:
We have built three models among which the Random Forest Regressor model shows the best result through which we can say 83.75% variability of expenses can well be explained by predictor variables and which yields comparatively low RMSE value so our predicted expense through this model will not vary too much from the actual expense.

Recommendations:
The accuracy can be much more enhanced with the following recommendations:
• The data sample size is relatively small in this case, especially with a perspective of applying this in real world.
• The number of features is also limited in this dataset. With an addition of 5 or more valid/logical features, the predictions can be improved much further.
• We can try converting the Expense column to a normal distribution using log or square root transformation for removing the skewness.
• Future enhancements to this project could include experiments with additional predictive models such as Gradient Boosting or SVM models. Improved accuracy of the linear regression models is likely with additional preprocessing of the data to better conform to the assumptions of linear modeling.

Future Work:
• We plan to take this project further as health is center of everyone’s life and every part of our life relies on good health.
• We intend to develop an application to predict possible medical costs using PyCharm editor on AWS platform by plugging in basic details such as age, sex, smoker, children, region and then pressing a submit button.
