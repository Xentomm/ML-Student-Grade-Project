<h2 align="center">End to end machine learning project to predict math score using data gathered from students.</h2>

<p align="center">
  <a href="#key-points">Key Points</a> •
  <a href="#how-to-use">How To Use</a> •
</p>

## Key Points

* Complete CI/CD Pipeline ready for deployement
* Basic Flask setup that can be extended by adding CSS
* Multiple Regression models tested 

## How To Use

```bash
# Clone this repository
$ git clone https://github.com/Xentomm/ML-Student-Grade-Project.git

# Go into the repository
$ cd ML-Student-Grade-Project

# Install dependencies(on venv)
$ python -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt

# Run model training
$ python src/components/data_ingestion.py

# Run the app
$ python application.py

# Go to the link in the terminal(http://127.0.0.1:5000/predictdata) and fill up the form
```
