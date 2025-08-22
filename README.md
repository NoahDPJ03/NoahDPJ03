## Directory

- [How to Run](#how-to-run)  
- [Projects](#projects)  
  - [Expectation Maximization Proj.](#expectation-maximization---monte-carlo-markov-chain-vs-responsibilities-methods)  
  - [Salary Data Neural Net & Model Comparisons](#neural-network--model-comparison-eda--data-cleaning-on-salary-data)  
  - [Pokemon Creator](#pokemon-creator---work-in-progress)  
- [About](#about)

## How to Run

Mostly all notebooks are built in Google Colab. You can open and run them using the Colab badge or by uploading to your Google Drive.

## Projects

| Project | Description | Tools / Concepts | Links |
|--------|-------------|------------------|-------|
| **Expectation Maximization – Monte Carlo Markov Chain vs. Responsibilities Methods** | Developed and analyzed two EM algorithms — the traditional Responsibility Method and a custom MCMC-based approximation — to compare effectiveness in estimating parameters of mixed distributions. Built a data generator for mixed continuous/discrete distributions, automated large-scale testing, and visualized convergence/error patterns. | **Tools:** Matplotlib, NumPy, functools<br>**Concepts:** MCMC, Nested Algorithms, Mixture Models, EM | [GitHub](https://github.com/NoahDPJ03/EM) |
| **Neural Network & Model Comparison, EDA, + Data Cleaning on Salary Data** | Cleaned and formatted data for neural networks, performed EDA, implemented a PyTorch model (~0.8 R²), and compared it to a RandomForestRegressor. | **Tools:** Pandas, Seaborn, Matplotlib, scikit-learn, PyTorch | [Dataset (Kaggle)](https://www.kaggle.com/datasets/mohithsairamreddy/salary-data) [GitHub](https://github.com/NoahDPJ03/Neural-Net-Salary-Data) |
| **Pokemon Creator – WORK IN PROGRESS** | A machine learning-powered Pokemon creator that predicts stats and generates Pokemon profiles. Features Random Forest predictions with confidence intervals and an interactive Streamlit app. AI generation features (Stable Diffusion + DistilGPT-2) are preserved in the codebase for local use. | **Tools:** Streamlit, Random Forests, PyTorch, Transformers (commented out for cloud deployment)<br>**Concepts:** ML Regression, Confidence Intervals, AI Image/Text Gen, Web Deployment | [GitHub](https://github.com/NoahDPJ03/pokemon-creator) |
| **Linear Regression from Scratch** | Built a linear regression model from scratch to explore the mathematics behind regression. Supported both univariate and multivariate cases, included gradient descent, and addressed multicollinearity using correlation matrices. | **Tools:** Pandas, Seaborn, Matplotlib, Scikit-learn (for comparison)<br>**Concepts:** Derivatives, Regression, Gradient Descent, Multicollinearity | [Dataset (Kaggle)](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025) [GitHub](https://github.com/NoahDPJ03/Linear-Regression-from-Scratch) |
| **Bloons TD EDA** | Explored Bloons TD 6 data by analyzing bloon types and their co-occurrences. Used dimensionality reduction to visualize patterns. | **Tools:** PCA, Data Melting/Expanding | [Dataset (Kaggle)](https://www.kaggle.com/datasets/brandonconrady/bloons-tower-defense-6-rounds-1140) [GitHub](https://github.com/NoahDPJ03/Bloons-TD-Analysis/tree/main) |
| **Kruskal, Prim, Dijkstra, and Chomp Game** | Implemented Kruskal’s, Prim’s, and Dijkstra’s algorithms from scratch and applied them to user-generated graphs. Developed strategies for Chomp using game theory. | **Tools:** NumPy, Matplotlib<br>**Concepts:** Graph Theory, Game Theory, Adjacency Matrices | [GitHub](https://github.com/NoahDPJ03/KrusPrimDijkChomp) |
| **Markov Chains, Monte Carlo, Generating Functions** | Explored Markov Chains and Monte Carlo methods for domino tilings, along with generating functions derived from recurrence relations. | **Tools:** NumPy, SymPy, Matplotlib<br>**Concepts:** MCMC, Recurrences, Generating Functions | [GitHub](https://github.com/NoahDPJ03/Markov_MonteCarlo_GF) |
| **Exploratory Data Analysis + Linear Regression – Esports** | Performed EDA and linear regression on esports player/team earnings data, exploring features like tournament counts and game types. | **Tools:** Pandas, Matplotlib, Seaborn, scikit-learn<br>**Concepts:** Linear Regression, EDA, Boxplots | [Dataset (Kaggle)](https://www.kaggle.com/datasets/jackdaoud/esports-earnings-for-players-teams-by-game) [GitHub](https://github.com/NoahDPJ03/EDA-Esports-Earnings) |

## About

All repositories serve to track my learning and share my work in data science, machine learning, statistics, and computer science.
