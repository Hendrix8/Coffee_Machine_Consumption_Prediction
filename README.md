# Coffee Machine Consumption Prediction

The ability to accurately forecast energy requirements not only facilitates in-
formed decision-making, but also enables efficient resource allocation and demand-
side management. In the domestic context, coffee machines are among the most
frequently used devices, contributing to a significant part of energy consump-
tion. Therefore, accurately predicting energy usage can lead to significant energy
savings and improved user experience.
Traditional time series analysis techniques often fall short in capturing the
complex, non-linear relationships inherent in energy consumption patterns. To
overcome this limitation, recurrent neural networks (RNN) have emerged as
powerful tools for modeling sequential data due to their ability to capture tem-
poral dependencies. In particular, the LSTM (Long Short-Term Memory) and
GRU (Gated Recurrent Units) architectures have gained prominence for their
ability to handle long-term dependencies and mitigate the problem of vanishing
gradients.
In this work, the application of RNN, LSTM and GRU models to predict 120-
minute coffee machine consumption time series was investigated, using whole-
house energy consumption information for each 120-minute period.
Below are graphs of home consumption and coffee machine consumption for
three random 120-minute windows.
2 Applied Methods
2.1 Data Normalization
Normalization was first applied to the data by dividing by the true maximum
value. This is necessary because time series data often exhibit significant vari-
ations in size and scale. Normalization helps bring the data into a consistent
range, and ensures that all features contribute proportionally to the analysis
and model training process, preventing any particular feature from dominating
due to its larger values. Also, outliers can distort statistical measures and affect
model performance.
3
