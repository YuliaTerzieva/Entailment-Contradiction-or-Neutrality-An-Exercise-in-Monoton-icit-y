# Entailment, Contradiction, or Neutrality? An Exercise in Monoton(icit)y 


 
Implementation of a rule-based model for Natural Language Inference. 
For a full description of the methods used and our motivation please consult with the pdf. 

The implementatio of the Methods Section is in the Python Notebook. 

To generate the confusion matrices presented in the Result Section of the paper please run all the code without changes and fill in the desired parameters in the last cell. 

We recommend runnning the code in Google Colab and importing the csv file, which is needed for a smaller dataset curated specifically for the tree model. 
This dataset is a subset if the training set including only sentences with the most common sentence structure of premise being ('NOUN', 'ADP', 'PUNCT'), and hypothesis being ('NOUN', 'ADP', 'PUNCT'). 
