---
layout: page
title: Projects
subtitle: My myriad experiences doing Data Science
---

+ **[Knowledge Transfer in Reinforcement Learning](https://github.com/Regressionist/Meta-Reinforcement-Learning)**: Analyzed RL agents in the context of generalizing prior experiences to new unseen environments. Trained the agent using Deep-Q leaning with experience replay algorithm coupled with different transfer learning regimes. Employed the policy learned in one environment to evaluate the difference in the agent’s learning time in a second environment


+ **[Semantic Segmentation](https://github.com/Regressionist/Semantic-Segmentation-UNet)**: Implemented the Unet architecture with pixel shuffle for dense prediction on Cityscapes dataset. Devised a new training loss function to enforce background prediction for inconsistent structures. Achieved 0.826 mean IoU on the holdout set


+ **[DeepRecommender](https://github.com/Regressionist/Autoencoder-based-Recommendation-System)**: Developed a model for the rating prediction task in recommender systems using Autoencoders. Refined the model using dense refeeding (to combat the sparsity of the user-item matrix) and dropout regularization. Achieved 0.925 RMSE on the holdout set of Amazon android apps ratings


+ **[Financial time-series forecast](https://github.com/Regressionist/Stock-prediction-Dual-Attention-based-RNN-)**: Devised a Dual-Stage Attention-Based RNN to predict DJIA stock closing prices for the next 50 days from historic data. Incorporated feature engineering techniques including moving averages and exponential moving averages. Achieved 92% directional accuracy on the test set


+ **[Image Inpainting](https://github.com/Regressionist/Image-Inpaiting-DCGAN)**: Implemented DCGAN architecture (Deep Convolutional Generative Adversarial Networks) architecture to fill in the missing portions in an image (inspired by this [paper](http://iizuka.cs.tsukuba.ac.jp/projects/completion/data/completion_sig2017.pdf)). With a fully-convolutional neural network, the images produced are both locally and globally consistent


+ **[Face Detection and Recognition](https://github.com/Regressionist/Face-Detection-and-Recognition)**: Designed a 8 layered CNN for person recognition and bounding box regression. Augmented the training dataset by horizontal flipping and adding gaussian noise to the images. Model achieved a classification accuracy (for recognizing the employee by employee ID) of 94% on test set and 0.71 IoU


+ [**Flight Delay Prediction**](https://github.com/Regressionist/Flight-Delay-Prediction): Worked in a team of three to design a model to predict flight delays for flights departing from JFK airport based on historical data of flight delays, past weather data and US Bank holidays data. Achieved 0.78 AUC using ensemble methods


+ [**Sentiment analysis**](https://github.com/Regressionist/Sentiment-analysis): Classified Amazon reviews as postive and negative using RNN and bidirectional multilayer LSTM. Achieved classification accuracy of 0.952 on the test set


