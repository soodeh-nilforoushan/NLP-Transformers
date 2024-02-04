# NLP-Transformers

These projects show how we use different types of transformers with an example.

1)The attention mechanism allows neural networks to learn very long-range dependencies in sequences Longer range than LSTM, a type of RNN Attention was created for RNNs, but transformers use attention only, while doing away with recurrent part
2) Transformers are big and slow but computations can be done in parallel (unlike RNNs!)

Possible Pre-training task:
1- Causal LM(Autoregressive LM) (like GPT): it trains the model based on previous data point to predict the next data point.
2 Masked LM (Autoencoding LM)(like BERT): it trains the mode of the model based on the past and future data points.
