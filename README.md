# MinMax-BNN
Minimax Bayesian Neural Networks (BNNs) . 
The code here provides some experiment results for the paper "Minimax Bayesian Neural Networks" (Code based on CTRL-LDR model), the corresponding results can be found in the jupyter notebook.
Minimax BNNs forms a two-player game between a deterministic neural network and a sampling stochastic neural network, and is a conservative formulation in contrast to the classical BNNs, it 
controls the variance by the minimax loss requirements through a scalar called "radius". Through this minimax Bayesian formulation we can provide reference for the variance setting for the classical BNNs, 
and quantify how large the maximal coding rate reduction loss is used in the closed-looped NNs. For more information, please see the paper.
