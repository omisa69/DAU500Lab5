# DAU500Lab5
Time Series Forecasting and Music Generation Using Recurrent Neural Networks

This project explores the performance of advanced neural network architectures, including Recurrent Neural Networks (RNNs), Long Short-Term Memory (LSTM) networks, and Gated Recurrent Units (GRUs), on the Bach Chorales dataset. The study addresses challenges such as slow convergence and the vanishing gradient problem often encountered with traditional RNNs.

Normalization techniques such as batch normalization and layer normalization were implemented to improve gradient stability and accelerate training. Batch Normalization exhibited slightly better performance than Layer Normalization, leading to faster convergence and improved stability.

Additionally, LSTM and GRU architectures were evaluated to overcome the inherent limitations of RNNs. Both models achieved superior performance, effectively capturing the temporal dependencies in the music data. While the LSTM demonstrated excellent modeling capabilities, the GRU achieved comparable results with lower computational requirements, making it the most efficient model in this study.

The project highlights the importance of combining advanced neural architectures with effective normalization techniques for sequential data tasks. The findings underscore the GRU as a strong candidate for modeling temporal dependencies, balancing high performance with computational efficiency.
