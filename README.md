# ML-Ops-CML
To automate a machine  learning model with the help of CML (Continuous Machine Learning) with GitHub Actions.

For this a **Tensorflow Regression** model is created in `model.py` and python libraries requirements in `requirements.txt`. <br/>
<br/>
A GitHub Action with [CML](https://cml.dev/) is made inside `.github/workflows/` which will train the model and find out the metrics and plot a graph on it. <br/>
<br/>
This GitHub Action will work on **PUSH events** and will train the model and give the metrics.
