# ensemble

All codes are provided as Jupyter Notebook (*.ipynb) files and were executed in the Google Colab environment with a GPU hardware accelerator. To run the notebooks, it is necessary to adjust the dataset paths in the first code cell, for example:

data = pd.read_csv('cvd/data1.csv')


All relevant *.csv files are located in the dataset/cvd directory and should be correctly referenced before execution. The dataset was obtained separately and is also publicly available at Covid-19-Patient-Health-Analytics
.

There are two main Jupyter Notebook files:

Correlation and Variance Threshold.ipynb – Implements the Correlation and Variance Threshold feature selection algorithms.

IG_Fisher_ChiSq.ipynb – Implements Information Gain (IG), Fisher Score, and Chi-Square feature selection algorithms.

All algorithms were executed using a 5-fold cross-validation procedure.

For overall evaluation and presentation of the proposed method, the Ensemble Eval.ipynb notebook was used.
