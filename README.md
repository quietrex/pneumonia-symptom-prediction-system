# Predicting COVID-19 for Chest X-Ray images using Deep Learning (CNN)
A system that can predict pneumonia from X_Ray image compliment with RPA workflow

## About
This project is a submission from a 2-day mini AI-thon organized by Skymind

## Achievement
1st - First place

## Aim
To assist the healthcare industry by sending covid-19 diagnosis result directly from the radiologist to the doctors to avoid human intervention, complementing with RPA workflow to avoid iterative process.

## Technology
Deep Learning CNN, Web Api, Robotic Process Automation (RPA)

![technology](/image/technologies.PNG)

## Workflow
![workflow](/image/workflow.PNG)

## How to deploy the webapp

Download h5 file: https://drive.google.com/file/d/1scqgXosKhmHqj7b5dKrL2LGoyBeFMVJ3/view?usp=sharing
OR
open ClassificationModelWithCNN_1.h5

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



## Contributors

```
1. Chan Kuok Hong/Rex Chan
2. Muhammad Laziem Bin Shafie
3. Muhammad Amiruddin Bin Bustaman
4. Rehan Shahid

```


