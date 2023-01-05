Cemhan Kaan Özaltan
21902695

In order to run q2main.ipynb, Kaggle or JupyterLab can be used with the "Run All" option or by running each 
cell one by one. While implementing the homework, I used Kaggle. Data files must either be in the same directory 
with the notebook, or the paths of the read_csv calls must be changed accordingly. My implementation starts with a 
data analysis stage where I visualize the training and validation datasets which I load from the csv files using 
Pandas and plot using Seaborn. I then convert the dataframes into NumPy arrays and fit my model onto the data. 
I then make predictions using the validation dataset. I also tuned my hyperparameters according to this stage's 
results during my implementation. Finally, I calculate the confusion matrix with a function and display it with 
a Seaborn heatmap. I then repeat this fit and predict process using a Dirichlet prior. The outputs are all 
labeled with what they are for better understandability.