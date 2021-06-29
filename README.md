# Customer Retention


## Introduction
In this repository,I have performed the end to end Exploratory Data Analysis, and idenfitied the characteristics of the customers that are more likely to churn, and  after EDA I used the main features to build model and lately, have deployed the model.

<<<<<<< HEAD
## For EDA, please refer to : Churn Analysis - EDA.ipynb
## For Model Building, please refer to: Churn Analysis - Model Building.ipynb
## For Model Deployment, please refer to app.py


## Creating the flask API
=======
### For EDA, please refer to : EDA_TCP.ipynb
### For Model Building, please refer to: Predictive_TCP.ipynb
### For Model Deployment, please refer to app.py


### Creating the flask API
>>>>>>> cd415c2655428772f8e3b8e31b4ac379e4673c40

```
app = Flask("__name__")
```

The loadPage method renders our home.html.
```
@app.route("/")
def loadPage():
	return render_template('home.html', query="")
```

The predict method is our POST method, which is basically called when we pass all the inputs from our front end and click SUBMIT.
```
@app.route("/", methods=['POST'])
def predict():
```
  
The run() method of Flask class runs the application on the local development server.
```
app.run()
```

Go to Terminal or Anaconda Prompt, and run the below query.
```
python app.py
```


Below message in Python shell is seen, which indicates that our App is now hosted at http://127.0.0.1:5000/ or localhost:5000
```
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```


<<<<<<< HEAD
## HERE'S HOW OUR FRONTEND LOOKS LIKE:
=======
Here is the User Interface:
>>>>>>> cd415c2655428772f8e3b8e31b4ac379e4673c40

![Customer Retention](https://github.com/aman-ku/Telecom-Customer-Churn/blob/f2ed34ca267640f3c7f5a1c534f1aad4a3a10b1b/images/Screenshot%20from%202021-06-29%2020-54-03.png)
![Customer Retention](https://github.com/aman-ku/Telecom-Customer-Churn/blob/46e332b40562667d115bae2905333da8558eec51/images/Screenshot%20from%202021-06-29%2020-54-25.png)
![Customer Retention](https://github.com/aman-ku/Telecom-Customer-Churn/blob/46e332b40562667d115bae2905333da8558eec51/images/Screenshot%20from%202021-06-29%2020-54-08.png)
