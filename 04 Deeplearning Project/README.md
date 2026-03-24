# Project Setup

## creating python environment
```
conda create -p venv python==3.11 -y
```

## activating python environment
```  
conda activate venv/
```

## installing dependencies and libraries
```
pip install -r requirements.txt
```

### Determining the optimal number of hidden layers and neurons for an Artificial Neural Network (ANN) 
This can be challenging and often requires experimentation. However, there are some guidelines and methods that can help you in making an informed decision:

- Start Simple: Begin with a simple architecture and gradually increase complexity if needed.
- Grid Search/Random Search: Use grid search or random search to try different architectures.
- Cross-Validation: Use cross-validation to evaluate the performance of different architectures.
- Heuristics and Rules of Thumb: Some heuristics and empirical rules can provide starting points, such as:
  -    The number of neurons in the hidden layer should be between the size of the input layer and the size of the output layer.
  -  A common practice is to start with 1-2 hidden layers.
