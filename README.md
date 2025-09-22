# FIFA-prediction
A machine learning model to predict the players overall performance.

This is a project where I built a machine learning model to predict a FIFA player's Overall rating. I wanted to see if I could accurately estimate a player's rating based on their individual skills and attributes.

I Merged seven years of FIFA data into one master file and cleaned it up by standardizing columns like Value, Wage, and Height.
Created some new features, like calculating a player's experience in days at their club. I also grouped rare categories for columns like Club and Nationality.
Used scikit-learn to create a pipeline that automatically handles missing values, scales numbers, and one-hot encodes text data.
I trained a RandomForestRegressor to make the final predictions.
