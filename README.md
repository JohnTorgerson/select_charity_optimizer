# Alphabet Soup Charity

### Evaluating charity applications using nueral network machine learning

##### Authors:
* John Torgerson (JohnTorgerson)
---

##### Tools & Supplies:
* alphabet soup charity database

* Python, Pandas, Matplotlib, Scikit-learn, TensorFlow, and KerasTuner
---

### Guide to Repo Contents:

* In Folder `AlphabetSoupCharity_Optimization6.h5` is a saved copy of the learning model:
    1. `Folder.Series` All the models results running through all epochs
    ***too many to bother listing***
    
* In folder, `Resources` is the following:
    1. `charity_data.csv` is the raw charity data
* `AlphabetSoupCharity_Optimization1.ipynb` is a first neural network with optimization modifications 
* `AlphabetSoupCharity_Optimization2.ipynb` is a second neural network with optimization modifications
* `AlphabetSoupCharity_Optimization3.ipynb` is a third neural network with optimization modifications
* `AlphabetSoupCharity_Optimization4.ipynb` is a fourth neural network with optimization modifications
* `AlphabetSoupCharity_Optimization5.ipynb` is a fifth neural network with optimization modifications
* `AlphabetSoupCharity_Optimization6.ipynb` is a sixth neural network with automated optimization modifications
* `AlphabetSoupCharity.ipynb` is the primary notebook created to process and test the data
* `AlphabetSoupCharity.h5` is a saved copy of the original learning model
* `AlphabetSoupCharity_Optimization1.h5` is a saved copy of the learning model; 1st modification
* `AlphabetSoupCharity_Optimization2.h5` is a saved copy of the learning model; 2nd modification
* `AlphabetSoupCharity_Optimization3.h5` is a saved copy of the learning model; 3rd modification
* `AlphabetSoupCharity_Optimization4.h5` is a saved copy of the learning model; 4th modification
* `AlphabetSoupCharity_Optimization5.h5` is a saved copy of the learning model; 5th modification
* `InvestmentPlot.png` is an image file showing a quick test of investment size on successful and not successful charities
* `ReadME.md` is the repo contents file you're currently viewing
* `Written_Analysis.md` is the workflow, analysis, and summary of this deep learning set of models
    
---

### Observations:
* The bulk of the work that goes into a machine learning project is in the preprocessing.
* Once the data is cleaned, the computer does most of the work to deliver the results we're seeking.
* That being said, there is still a lot to learn and understand about how, when, and which machine learning tools should be implemented.
* The comprehension mastery of what is going on behind the scenes could take a person years to learn and practice.
---

### Credits and Special Thanks

* Dr. William Vann for experiencing a similar preprocessing challenge with me. Each of us found our own solutions. He used a forloop for bucketing his categories, while I decided to take a direct dataframe drop, concatenation, and sorting track to achieve the result.