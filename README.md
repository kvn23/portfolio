# Project Portfolio

This repository showcases some projects (or parts of them) I worked on during the past years.

---

### 1 Steel Surface Defect Classification

This was a small project during my employment as a research assistant at the University of Würzburg under supervision of a PhD student. The main task was to find a dataset related to AI-assisted maintenance or quality assurance in manufacturing, which was then used to develop a classifier model with XAI augmentations. The overall purpose to the PhD student was to have a working example model, on which a user experiment can be built upon. The research purpose was to find out, how the information from the XAI augmentations impacts user confidence and performance of an AI driven decision support system. For me, this project offered an opportunity to learn about and implement basic explanations for machine learning results, such as SHAP and LIME. Furthermore it gave me a broader perspective on the utility of simple ML models in smart manufacturing, as well as fresh knowledge about the conversion of intially unstructured data such as images into structured tabular data.

Dataset(s):
- Steel Plates Faults Data Set (http://archive.ics.uci.edu/ml/datasets/steel+plates+faults)

Model Purpose:
- Classify different steel surface defects.
- Offer explanations for classifications.

Main libraries: Scikit-Learn, SHAP, LIME, Anchors (alibi)

**Jupyter Notebook: [Classifying Steel Surface Defects with Explanations][1]**

[1]:https://nbviewer.jupyter.org/github/kvn23/portfolio/blob/main/Steel%20Surface%20Defect%20Classifier/steelsurface_classification_xai.ipynb

---

### 2 Iris / Credit Risk / Heart Disease Classification

These notebooks were part of my Master's thesis on Explainable Artificial Intelligence. Foremost,they served as working examples for a user survey, in which participants were asked to rate different representations of ML result explanations. Additonally, they were used to benchmark the implemented ML algorithms and explanation methods. In the first coding steps, these three individual datasets and the differen XAI libraries were a good training for data cleaning and preprogressing skills using Pandas, different scalers, etc.. Subsequently, I was also able to practice the implementation of different ML algorithms for tabular data. Overall, it was a tremendous learning opportunity to get a deeper understanding of explanation methods and figuring out libraries to implement them on working projects.

Dataset(s):
- Iris Data Set (https://archive.ics.uci.edu/ml/datasets/iris)
- Statlog (German Credit Data) Data Set (https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))
- Heart Disease Data Set (https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

Model Purpose:
- Classify iris species / credit risk of loan applicants / patients in risk of heart disease
- Utilize different methods to explain result outcomes

Main libraries: Scikit-Learn, CatBoost, SHAP, LIME, Anchors (alibi), Counterfactual Instances (alibi)

**Jupyter Notebooks:**
- **[Explaining Iris Species Predictions with *Anchors*, *LIME* and *Counterfactual Instances*][2]**
- **[Explaining Credit Risk Predictions with *Anchors* and *LIME*][3]**
- **[Explaining Credit Risk Predictions with *Counterfactual Instances*][4]**
- **[Explaining Heart Disease Predictions with *Anchors* and *LIME*][5]**
- **[Explaining Heart Disease Predictions with *Counterfactual Instances*][6]**

[2]:https://nbviewer.jupyter.org/github/kvn23/portfolio/blob/main/ML%20Prediction%20Explainers/iris_classification_xai.ipynb
[3]:https://nbviewer.jupyter.org/github/kvn23/portfolio/blob/main/ML%20Prediction%20Explainers/credit_risk_anchors_lime.ipynb
[4]:https://nbviewer.jupyter.org/github/kvn23/portfolio/blob/main/ML%20Prediction%20Explainers/credit_risk_counterfactuals.ipynb
[5]:https://nbviewer.jupyter.org/github/kvn23/portfolio/blob/main/ML%20Prediction%20Explainers/Heart%20Disease_AnchorsLime.ipynb
[6]:https://nbviewer.jupyter.org/github/kvn23/portfolio/blob/main/ML%20Prediction%20Explainers/Heart%20Disease_Counterfactuals.ipynb

---

### 3  Turbofan Engine RUL prediction

This was one of the first datasets and machine learning projects I personally ever coded on. For a seminar thesis, my supervisor threw me in at the deep end by benchmarking different algorithms on this dataset. At the beginning of this project I barely knew how to code in Python, let alone building machine learning models. By the end, this project had gave me a glimpse into CNN and LSTM models, as well as handling time series data. In this, case i settled for the implementation of a CNN as proposed by [Xiang Li (2018)](https://www.sciencedirect.com/science/article/abs/pii/S0951832017307779).

Dataset(s):
- Turbofan Engine Degradation Simulation Data Set

Model Purpose:
- Predict Remaining Useful Life of a Jet Engine

Main libraries: Tensorflow, Keras

---

