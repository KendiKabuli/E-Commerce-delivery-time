PROJECT OVERVIEW

- This project uses linear regression to predict the delivery days for e-commerce orders based on dataset features such as the purchase hour and the purchase day of the week, it is part of my machine learning practice exploring supervised learning using python

Language - Python 

Libraries used - Pandas, Numpy, matplotlib, seaborn, scikit-learn


OBJECTIVES

- To analyze e-commerce order data

- To build a linear regression model to predict the delivery times

- To predict actual vs predicted delivery days

- To evaluate the model performance using metrics like the R² score and the mean squared error(MSE)

KEY LEARNING POINTS

- Data pre-processing using pandas and numpy

- Exploratory data analysis(EDA) with seaborn and matplotlib

- Building and evaluating regression models with scikit-learn

- Understanding model performance and overfitting


HOW TO RUN

- Clone the repository from GitHub to your local computer.

- Install the required Python libraries listed in the requirements.txt file.

- Open the Jupyter Notebook located in the notebooks/ folder.

- Run all the cells in the notebook to train the model and view the results.

MY INTERPRETATION

- The performance metrics are relatively low which means that the model predictions don't yet match the actual delivery days very closely. However, this is expected because the model only used one subset of the full e-commerce dataset that i found online on kaggle ( i used the orders file only). Other related files in the dataset (e.g., customers, payments, shipments) likely contain additional information that would improve accuracy.

WHAT I LEARNED FROM THIS

- Using limited features can signiicantly reduce the models accuracy

- Model accuracy is not always the main goal - understanding data relationships is just as important

- Good results often come from better data preparation and feature selection, not just complex algorithms

- Its important to evaluate and interpret metrics, not just report them blindly or overlooking them

FUTURE IMPROVEMENTS 

- Combine multiple datasets (orders, customers, products, and shipments)

- Add new features like shipping method, payment type, and customer location

AUTHOR - ANNJOY KENDI KABULI


