# Health-care-Heart-attack-possibility
# 1.0 Heart Attack
* it happens when oxygen can't reach the heart in a reasonable amount, as arteries are filled with fats preventing blood to reach the heart.

* Patients describe it as crushing, which could radiate to the arm, jaw, or back.
Some people experience it in silence, maybe they just severe nausea or are short of breath

* for women and the elderly, they might look weak and tired.
And many people especially diabetes, which affects nerves that carry pain, a heart attack might be silent

* Aspirine might help a lot, and might be prevented with exercise, and a healthy diet.

For competition: [Kaggle](https://www.kaggle.com/nareshbhat/health-care-data-set-on-heart-attack-possibility)

#  Findings and observations.
1.   As observed from the Logistic Regression model, data is linearly separable
2.   Women have higher rates of heart diseases than males.
3.   heart attacks mostly happen at age 50-55 for men and women, but men have a higher risk than women at age 40-45
4.  pain caused by non- angina have no clear definition or correlation. But I  find the anginal pain have reasonable higher correlations with some columns, if these symptoms don't appear on the patient they would have a higher probability of having non-anginal pain
5.  most people have a high risk at cholesterol level between 200 and 300
6.  Data set doesn't reveal clear relation between blood sugar and risk.


# Conclusions
* To prevent heart disease risk you may consider the following
  * make cholesterol level less than 200
  * From the internet:
    * Eat healthy food
    * do many exercises
    * do regular heart checks especially between age 50-55


#  Limitations

* Dataset is so small, and final results can't be generalized to all population, the test set is already very small, small error doesn't indicate the low generalized error; as it's so small

* Especially it's something related to people's health, more accuracy is required. data should be larger to generalize the error.

* Dataset provided some features, out of many features originally published online, I don't trust his judgment, as it's wasn't known what algorithm and what criteria he used to filter the columns, may be there are some other columns that have a more important weight

* threshold for sugar level doesn't reveal any meaningful output, I suggest finding some other threshold, or just publishing blood sugar as a continuous variable, and then I will try to see the relation.


Scores:

![image](https://user-images.githubusercontent.com/69484554/143659269-1e950f2c-14c4-45cf-9645-43628d53b8b8.png)
