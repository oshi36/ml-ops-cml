# ML-Ops-CML
To automate a machine  learning model with the help of CML (Continuous Machine Learning) with GitHub Actions.

For this a **Tensorflow Regression** model is created in `model.py` and python libraries requirements in `requirements.txt`. <br/>
<br/>
A GitHub Action with [CML](https://cml.dev/) is made inside `.github/workflows/` which will train the model and find out the metrics and plot a graph on it. <br/>
<br/>
This GitHub Action will work on **PUSH events** and will train the model as you do commit <br/>
After the training model performance wil be send as a reply to the commit and to the registered GitHub Email as well as shown in the image below

### Model Performance details as a comment <br/>
<img src="https://github.com/oshi36/ml-ops-cml/blob/main/plot.png" width="500" height="500">
<br/>
<br/>

### Model Performance details in an Email <br/>
<img src="https://github.com/oshi36/ml-ops-cml/blob/main/email_image_updated.jpg" width="500" height="500">

