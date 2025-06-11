Explorations in probabilistic reasoning, structure learning and decision theory. 

## Project 1: Event Inference in Financial Markets

Investigates the relationship between executive social media activity and short-term stock price movement. Using a simple probabilistic model, I:

- Represent CEO posts as observable variables
- Model stock price change as a hidden variable
- Estimate conditional probabilities based on historical patterns
- Compute expected utility for trading strategies under uncertainty

### Techniques
- Bayesian Inference
- Expected Utility Maximization
- Discrete Probabilistic Modeling


## Project 2: Structure Learning on Simulated Health Data

Applies structure learning and probabilistic inference to a dataset of 10,000 simulated patients. The goal is to uncover latent relationships between lifestyle factors and health outcomes through learned Bayesian networks.

### Steps
- Build a manually specified Bayesian Network and learn CPTs from data
- Apply structure learning algorithms:
  - Hill Climb Search
  - Exhaustive Search
  - Tree Augmented Naive Bayes (TAN)
- Evaluate structures using Bayesian Information Criterion (BIC)
- Select the most effective model for further inference


## Tools & Libraries

- `pgmpy`
- `pandas`, `numpy`, `matplotlib`
- `networkx`
- `scikit-learn` (for preprocessing and metrics)
