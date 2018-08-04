# New-York-Taxi-Duration
This project was a part of a kaggle competition , where given a certain pickup and dropoff coordinates, time we had to predict the duration of the trip.<br>
I have not uploaded the training dataset, you can easily download the files from here https://www.kaggle.com/c/nyc-taxi-trip-duration/data <br>
After executing all the lines of code, 3 files are created
* mean_values.csv (the mean of the training dataset which will be used for testing time)
* var_values.csv(the standard deviation which will again be used at testing time)
* final_model.pkl (the final model where testing can be done).
Since there are 1.4 million data-point ,training such data will take a lot of time, so make sure you take subset of the data.
<br>
Also I have deployed this model into production using flask .
<br>
The Url is :
