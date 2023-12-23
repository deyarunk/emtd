# EMTD: Explainable Malicious Traffic Detection Model using Hybrid Deep Learning Techniques for Industrial IoT Networks
EMTD: Explainable Malicious Traffic Detection Model using Hybrid Deep Learning Techniques for Industrial IoT Networks

Motivated by data privacy and the need for highly accurate intrusion detection, we propose a novel method, called Fed-ANIDS. The latter leverages federated learning algorithms with anomaly detection to develop an effective and secure network intrusion detection system. To detect intrusions, we compute an intrusion score based on the reconstruction error of normal traffic using various AD models, including simple autoencoders, variational autoencoders, and adversarial autoencoders. to preserve privacy, federated learning allows each device or node in the network to train and share only its locally calculated parameters with a centralized server, rather than transmitting sensitive data.

In this repository you will find a Python implementation of Fed-ANID that allows to run experiments simulating different configurations of training an autoencoder-based and GAN-based models for intrusion detection in a distribued system. The experiments are performed on three well-known intrusion detection datasets, USTC-TFC2016, CIC-IDS2017, and CSE-CIC-IDS2018.
The code will be available upon publication
