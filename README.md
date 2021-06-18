# Customer Retention

In this repository,I have performed the end to end Exploratory Data Analysis, and idenfitied the characteristics of the customers that are more likely to churn, and  after EDA I used the main features to build model and lately, have deployed the model.

### For EDA, please refer to : EDA_TCP.ipynb
### For Model Building, please refer to: Predictive_TCP.ipynb
### For Model Deployment, please refer to app.py


### Creating the flask API

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


Here is the User Interface:

![Customer Retention](https://github.com/aman-ku/Telecom-Customer-Churn/blob/4f148545ee615ee1e6b3ffc0961b1d0b4bd85736/images/frontend.JPG)
