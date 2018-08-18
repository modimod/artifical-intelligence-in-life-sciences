# artifical-intelligence-in-life-sciences
Project for the masters course "Artificial Intelligence in Life Sciences" in Spring 2018

This Project was about multitask prediction of a molecule dataset in smiles notation. 
Goal was to train any machine learning model on a train set to get the best scores on a leaderboard dataset, which targets were unknown.

This repo consists of a LSTM model to predict the targets of every task.

Features of the model:
- sliding window over the sequence
- variable length sequences in a batch
- multitask learning
