This is an experiment for financial fraud detection.

I have used simulated PaySim data obtained through the related Kaggle challenge.
https://www.kaggle.com/datasets/ealaxi/paysim1

PaySim simulator is available here.
https://github.com/EdgarLopezPhD/PaySim

I have done a quick comparison of graph based neural networks 2D convolutional and basic feedforward networks. This far I haven't done proper hyper parameter tuning or considered matching parameter space sizes. 
The experiment was more to learn the financial fraud detection problem and graph based neural networks.

PaySim data set has less fraud data than normal non-fraud transactions. I have dealt with this problem by adjusting data proportions by discarding non-fraud transactions and adding extra weight in learning from fraud data. 
