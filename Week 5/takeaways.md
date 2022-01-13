# 1. Modern RNNs
- Exploding gradient problem is easy to detect.
- The reason of the exploding gradient problem in the simple RNN is the recurrent weight matrix WW. Nonlinearities sigmoid, tanh, and ReLU does not cause the problem.
- Both nonlinearity and the recurrent weight matrix WW cause the vanishing gradient problem.
- Orthogonal initialization of the recurrent weight matrix helps with the vanishing gradient problem.
- LSTM Architecture
  - The LSTM needs four times more parameters than the simple RNN.
  - The exploding gradient problem is still possible in LSTM on the way between h_t-1 and h_t
