# hERG-Toxicity-Prediction-Model
Machine Learning-based prediction model for hERG inhibition prediction.

**Introduction:**

Welcome to our repository, here we provide machine learning model to efficiently predict the hERG inhibition of target drug compounds in early stage of drug discovery process. 

**Dependencies:**

  - python=3.7
  - rdkit
  - chembl_webresource_client
  - seaborn
  - scikit-learn
  - pickle5
  - jupyter
  - molvs
  - python-graphviz
  - pydotplus


**Execution:**

Use Jupyter notebook to execute the code, download all the input files and hERG_inhibition.pkl from the tab “Tag”.

Prepare your input file containing SMILES in .csv format and name the column as “SMILES”.

Make sure the paths of model, hERG_inhibition.pkl file and input files before executing the code file named as hERG_inhibition_Prediction_model.ipynb.

**Output:**

Our model generates output in binary value (1 or 0), where 1 indicates compound to be inhibitor, while 0 indicates non-inhibitor.

**Note:**

To access and download the prediction model file in .pkl format and input feature file, please refer to the tab "Tag --> v2.3.4".

**Authors:** 

Maninder Singh, Bilal Shaker, Jin Hee Lee, Sunghwan Choi, Sanghee Yoon, Shaherin Basith, Minghua Cui, Sunil Ahn, Haerim Han, Min SunYeom* and Sun Choi*
