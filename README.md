# wine-quality-prediction---deployment
Here, I using the wine dataset to predict the quality of wine. 

- The model is built using Random Forest Classifier.

- If the predicted wine quality is greater than 7, it is good quality. If the predicted wine quality is less tha 7, it is bad quality wine.

## About the DataSet:

- Size of the DataSet : 1599 records * 12 features

- The datasets consist of several features include:

- volatile acidity : Volatile acidity is the gaseous acids present in wine.

- fixed acidity : Primary fixed acids found in wine are tartaric, succinic, citric, and malic.

- residual sugar : Amount of sugar left after fermentation.

- citric acid : It is weak organic acid, found in citrus fruits naturally.

- chlorides : Amount of salt present in wine.

- free sulfur dioxide : So2 is used for prevention of wine by oxidation and microbial spoilage.

- total sulfur dioxide : is the amount of free + bound forms of SO2.

- pH : In wine pH is used for checking acidity.

- density : sweeter wines have a higher density.

- sulphates : Added sulfites preserve freshness and protect wine from oxidation, and bacteria.

- alcohol : Percent of alcohol present in wine.

- quality : Quality of the wine

## Deployment in AWS-Ec2:

I deployed the model in AWS using ec2 instance.
- I create a new ec2 instance and create new key.
- I add one more security group to allow permissions.
- After that open the winscp and enter the host name and user name then it divide into two pages.
- Go to project directory and upload all the required files to winscp window.
- Then open puttygen and download all the required libraries.
- It is very important to update using sudo. 
- After downloading all the libraries run the app.py using "python3 app.py" command.
- Then it starts running.
- Then go to AWS page--ec2 instance--connect--copy the generated url.
- paste the url on new window and add 8080 port to run our model.
- And it load the below page..
![Screenshot (10)](https://user-images.githubusercontent.com/103427929/212075031-ec113564-7e22-4f2a-826f-216e92581e75.png)
