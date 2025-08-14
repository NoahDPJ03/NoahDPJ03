# Hello! 

This profile showcases my portfolio of data science and machine learning projects, spanning from tutorial-based implementations to original work. Projects are created using Python and Jupyter notebooks, but often in Google Colab.

## Directory


[How to Run](#how-to-run)  
[Projects](#projects)  
- [Expectation Maximization Proj.](#expectation-maximization---monte-carlo-markov-chain-vs-responsibilities-methods)  
- [Salary Data Neural Net & Model Comparisons](#neural-network--model-comparison-eda--data-cleaning-on-salary-data)  
[About](#about)



## How to Run

Mostly all notebooks are built in Google Colab. You can open and run them using the Colab badge or by uploading to your Google Drive.

## Projects

| Project | Description | Tools / Concepts | Links |
|---------|-------------|------------------|-------|
| **Expectation Maximization – Monte Carlo Markov Chain vs. Responsibilities Methods** | Developed and analyzed two EM algorithms — the traditional Responsibility Method and a custom MCMC-based approximation — to compare effectiveness in estimating parameters of mixed distributions. Built a data generator for mixed continuous/discrete distributions, automated large-scale testing, and visualized convergence/error patterns. | **Tools:** Matplotlib, NumPy, functools<br>**Concepts:** MCMC, Nested Algorithms, Mixture Models, EM | [GitHub](https://github.com/NoahDPJ03/EM)
| **Neural Network & Model Comparison, EDA, + Data Cleaning on Salary Data** | Cleaned and formatted data for neural networks, performed EDA, implemented a PyTorch model (~0.8 R²), and compared it to a RandomForestRegressor. | **Tools:** Pandas, Seaborn, Matplotlib, scikit-learn, PyTorch | [Dataset](https://www.kaggle.com/datasets/mohithsairamreddy/salary-data) [GitHub](https://github.com/NoahDPJ03/Neural-Net-Salary-Data) |
| **Linear Regression from Scratch** | Built a linear regression model from scratch in Python to explore the mathematical foundations behind the algorithm, avoiding
scikit-learn during implementation. Started with simple univariate regression, then extended to multivariate cases, ultimately
creating a generalized function capable of modeling any number of independent variables. Managed, cleaned, and standardized
real-world datasets, implemented gradient descent, and addressed multicollinearity using correlation matrices. Compared final
model results to scikit-learn’s Linear Regression, achieving nearly identical $R^2$ values, demonstrating the correctness and
robustness of the implementation. | **Tools:** Pandas, Seaborn, Matplotlib, and Scikit-learn (for comparison)<br>**Concepts:** Derivatives, Linear Regression, Gradient Descent, Multicollinearity, Feature Engineering, Standardizing, etc. | [Dataset](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025) [GitHub](https://github.com/NoahDPJ03/Linear-Regression-from-Scratch) 
| **Kruskal, Prim, Dijkstra, and Chomp Game** | Implemented Kruskal’s, Prim’s, and Dijkstra’s algorithms from scratch in Python, applied them to user-designed graphs, and visualized MSTs and shortest paths. Also developed winning strategies for Chomp using game theory and symmetry tactics. | **Tools:** NumPy, Matplotlib<br>**Concepts:** Graph Theory, Adjacency Matrices, Game Theory | [GitHub](https://github.com/NoahDPJ03/KrusPrimDijkChomp)
| **Markov Chains, Monte Carlo, Generating Functions** | Created a notebook and LaTeX file exploring Markov Chains and Monte Carlo methods for 2×10 domino tilings, with generating functions derived from recurrence relations. | **Tools:** NumPy, SymPy, Matplotlib<br>**Concepts:** MCMC, Recurrences, Differential Equations, Graphs | [GitHub](https://github.com/NoahDPJ03/Markov_MonteCarlo_GF) |
| **Exploratory Data Analysis + Linear Regression – Esports** | Performed EDA and linear regression on player/team earnings data, analyzing relationships between earnings, game type, and tournament counts. | **Tools:** Pandas, Matplotlib, Seaborn, scikit-learn<br>**Concepts:** Linear Regression, Feature Engineering, Scatterplots, Boxplots | [Dataset](https://www.kaggle.com/datasets/jackdaoud/esports-earnings-for-players-teams-by-game) [GitHub](https://github.com/NoahDPJ03/EDA-Esports-Earnings)

## About

All repositories serve to track my learning and share my work in data science, machine learning, statistics, and computer science.
