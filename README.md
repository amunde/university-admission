# university-admission
# Content: Supervised Learning
## Project: Predicting student's chance of admit in university

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer. 

### Code

Template code is provided in the `university_admissions.ipynb` notebook file. The `Admission_Predict_Ver1.1.csv` dataset file has the required data.
### Run

In a terminal or command window, navigate to the top-level project directory that contains this README and run the following commands:

```bash
jupyter notebook university_admissions.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

## Data

The dataset contains several parameters which are considered important during the application for Masters Programs. (https://www.kaggle.com/mohansacharya/graduate-admissions).

**Features**
The parameters included are : 
1. GRE Scores ( out of 340 )
2. TOEFL Scores ( out of 120 )
3. University Rating ( out of 5 ) 
4. Statement of Purpose and Letter of Recommendation Strength ( out of 5 ) 
5. Undergraduate GPA ( out of 10 ) 
6. Research Experience ( either 0 or 1 ) 
7. Chance of Admit ( ranging from 0 to 1 )
