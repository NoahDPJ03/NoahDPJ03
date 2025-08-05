# Hello! 

This profile showcases my portfolio of data science and machine learning projects, spanning from tutorial-based implementations to original work. Projects are created using Python and Jupyter notebooks, but often in Google Colab.

## How to Run

Mostly all notebooks are built in Google Colab. You can open and run them using the Colab badge or by uploading to your Google Drive.

## Projects / Repositories

### Expectation Maximization - Monte Carlo Markov Chain vs. Responsibilities Methods
Developed and analyzed two Expectation Maximization (EM) algorithms—the traditional Responsibility Method and a custom
MCMC-based approximation—to compare their effectiveness in estimating parameters of mixed distributions. Implemented both
methods from scratch in Python, including robust E- and M-step functions, parameter updates, and log-likelihood tracking. Built
a randomized data generator to simulate mixtures of continuous and discrete distributions, automating large-scale tests without
user input. Visualized performance through convergence plots and statistical comparisons, revealing that the MCMC
approximation yielded results nearly identical to the standard method despite higher complexity.

- Tools: Matplotlib, Numpy, functools
- Concepts: Monte Carlo Markov Chains, Nested Algorithms, Mixture models, EM (obviously), etc.
- Check out the project here: https://github.com/NoahDPJ03/EM

### Neural Network($R^2 \approx 0.8$), EDA, + data cleaning on Salary Data 
Cleaned and formatted data (making the data appropriate for a neural network), did Exploratory Data Analysis (EDA) on data, 
and finally implemented a neural network using PyTorch, getting around a $0.8 R^2$ score.

- Tools: Pandas, Seaborn, Matplotlib, scikit-learn, Pytorch
- Dataset: https://www.kaggle.com/datasets/mohithsairamreddy/salary-data
- https://github.com/NoahDPJ03/Neural-Net-Salary-Data

### Linear Regression from Scratch
Built a linear regression model from scratch in Python to explore the mathematical foundations behind the algorithm, avoiding
scikit-learn during implementation. Started with simple univariate regression, then extended to multivariate cases, ultimately
creating a generalized function capable of modeling any number of independent variables. Managed, cleaned, and standardized
real-world datasets, implemented gradient descent, and addressed multicollinearity using correlation matrices. Compared final
model results to scikit-learn’s Linear Regression, achieving nearly identical $R^2$ values, demonstrating the correctness and
robustness of the implementation.

- Tools: Pandas, Seaborn, Matplotlib, and Scikit-learn (for comparison)
- Concepts: Derivatives, Linear Regression, Gradient Descent, Multicollinearity, Feature Engineering, Standardizing, etc.
- Datasets used: https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025
- Check it out here: https://github.com/NoahDPJ03/Linear-Regression-from-Scratch


### Kruskal, Prim, Dijkstra, and Chomp game
Implemented Kruskal’s, Prim’s, and Dijkstra’s algorithms from scratch in Python and applied them to user-designed graphs with custom adjacency matrices, ensuring each met problem-specific constraints like unique edge weights and minimum vertex degree. Visualized minimum spanning trees and shortest paths, and explained the underlying logic behind each algorithm’s behavior. Additionally, developed and tested winning strategies for the game of Chomp across different board types, including linear, square, and $2 \times n$ configurations, using game theory and symmetry-based tactics.

- Tools: numpy, matplotlib
- Concepts: Graph Theory, Adjancency Matrices, Game Theory, etc.
- Check it out here: https://github.com/NoahDPJ03/KrusPrimDijkChomp

### Markov Chains, Monte Carlo, Generating Functions
Notebook & LaTeX file with using markov chains and Monte Carlo on the 2x10 tilings of a domino board, also implements generating functions from recurrence relation.

- Tools: numpy, sympy, matplotlib
- Concepts: MCMC, recurrences, Differential Equations, Graphs, etc.
- Check it out here: https://github.com/NoahDPJ03/Markov_MonteCarlo_GF

### Exploratory Data Analysis + Linear Regression - Esports
This project goes into using Data Analysis techniques and some Linear Regression to look into Player/Team Earnings based on factors like the type of game played, total tournaments played, etc.

- Tools: Pandas, Matplotlib, Seaborn, Scikit-learn
- Concepts: Linear Regression, Feature Engineering, Scatterplot and boxplots, etc.
- Datasets: https://www.kaggle.com/datasets/jackdaoud/esports-earnings-for-players-teams-by-game
- Check it out here: https://github.com/NoahDPJ03/EDA-Esports-Earnings

### California House Pricing Prediction - Tutorial: https://www.youtube.com/watch?v=Wqmtf9SA_kk&t=54s&ab_channel=NeuralNine
A beginner-friendly project using linear regression to predict house prices in California based on features like location, income, and population. This project helps build foundational skills in data preprocessing, visualization, and regression modeling.

- Tools: Pandas, Matplotlib, Scikit-learn 
- Concepts: Linear Regression, Feature Engineering, Model Evaluation
- Check it out here: https://github.com/NoahDPJ03/California-House-Prediction

### Learning Random Forest Regression - Tutorial: https://www.youtube.com/watch?v=YUsx5ZNlYWc&t=601s&ab_channel=Ryan%26MattDataScience
A notebook focused on learning how Random Forest Regression works, implemented using Scikit-learn. It demonstrates how ensemble methods improve predictions compared to simpler models.

- Tools: Scikit-learn, NumPy
- Concepts: Decision Trees, Random Forests, Overfitting vs. Generalization
- Check it out here: https://github.com/NoahDPJ03/Learning-Random-Forest-Regression




## About

All repositories serve to track my learning and share my work in data science, machine learning, statistics, and computer science.
