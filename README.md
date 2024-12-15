# Multiple Evaluations on the MNIST Dataset (Ongoing)

This project explores the impact of different neuron architectures on the training, validation, and adversarial robustness (against FGSM) of neural networks, implemented in TensorFlow.

## Neuron Types Used:
- **Typical Neuron in a Dense Layer**:  
  `output = w * x + b`
  
- **Quadratic Neuron in a Dense Layer**:  
  `output = w1 * x^2 + w2 * x + b`

- **Cubic Neuron in a Dense Layer**:  
  `output = w1 * x^3 + w2 * x^2 + w3 * x + b`

- **Quartic Neuron in a Dense Layer**:  
  `output = w1 * x^4 + w2 * x^3 + w3 * x^2 + w4 * x + b`

## Results(in progress):
- When comparing models with identical layer configurations and ReLU activations, **linear** and **quadratic neurons** performed similarly in terms of training and validation.
- Models with **cubic** and **quartic neurons** demonstrated poor performance, especially during training.
