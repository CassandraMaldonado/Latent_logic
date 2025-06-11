Explorations in probabilistic reasoning, structure learning and decision theory. 

## Project 1: Event Inference in Financial Markets

Investigated the relationship between executive social media activity and short-term stock price movement. Using a simple probabilistic model, I:

- Represented the CEO posts as observable variables.
- Modeled stock price changes as a hidden variable.
- Estimated the conditional probabilities based on historical patterns.
- Computed expected utility for trading strategies under uncertainty.

### Techniques
- Bayesian Inference
- Expected Utility Maximization
- Discrete Probabilistic Modeling


## Project 2: Structure Learning on Simulated Health Data

Applied structure learning and probabilistic inference to a dataset of simulated patients. The goal was to uncover latent relationships between lifestyle factors and health outcomes through learned Bayesian networks.

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
