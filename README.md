# pneumonia-diagnosis-system
A system that can predict pneumonia from X_Ray image with RPA workflow

## About
This project is a submission from a mini AI-thon organized by Skymind

## How to deploy the webapp

Download h5 file: https://drive.google.com/file/d/1scqgXosKhmHqj7b5dKrL2LGoyBeFMVJ3/view?usp=sharing

```bash
pip install -r requirement.txt
cd webapp/
env FLASK_APP=predict_app.py Flask run --host=localhost
```
and then open http://localhost:5000/static/predict.html

## How to run ipynb file

```bash
pip install -r requirement.txt
jupyter lab 
```

## How to run RPA

```
1. Download UIPATH: https://cloud.uipath.com/iiumxzcsuyg/portal_/home
2. Open Project folder "CovidDiagnosisProcess"
3. Change the URL as needed
```


