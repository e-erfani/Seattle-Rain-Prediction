# Seattle_Climate_Prediction
Climate prediction is crucial for federal and local governments, farmers, and tourist agencies in order to plan well in advance for any decision-making or get ready for any likely weather/climate extremes. There are many factors contributing to climate prediction. In this project, I selected my city, Seattle, where many people (outside WA state) think  "it's always rainy in Seattle". 

I downloaded Seattle airport station data. As shown in the first figure in Climate_seattle.ipynb Junyper Notebook, the precipitation amount greatly reduces from winter to summer, and vice versa. It is also seen that precipitation and temperature are inversely associated. The second figure shows that monthly temperature can be used as a predictor for monthly precipitation via a linear regression showing a correlation coefficient of 0.9. 

In the second Jnyper Notebook (Predict_Seattle_Rain.ipynb), I investigated the accuracy of predicting rain for a day that is months in the future, if we know maximum and minimum temperature in previous years. I used various data analysis and a variety of machine learning algorithms (MLAs) and I then tuned MLAs' hyper parameters to determine the highest accuracy score, which was 68%. 

In the future, I will use feature engineering to determine predictors having higher correlation with rain. I might use additional input, too. All these will help enhance the accuracy score of prediction.
