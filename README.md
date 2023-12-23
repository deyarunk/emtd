# EMTD: Explainable Malicious Traffic Detection Model using Hybrid Deep Learning Techniques for Industrial IoT Networks
Motivated by data privacy and the need for highly accurate intrusion detection, we propose a novel method, called Fed-ANIDS. The latter leverages federated learning algorithms with anomaly detection to develop an effective and secure network intrusion detection system. To detect intrusions, we compute an intrusion score based on the reconstruction error of normal traffic using various AD models, including simple autoencoders, variational autoencoders, and adversarial autoencoders. to preserve privacy, federated learning allows each device or node in the network to train and share only its locally calculated parameters with a centralized server, rather than transmitting sensitive data.

In this repository, you will find a Python implementation of EMTD that allows you to run experiments simulating different configurations of training an autoencoder and Bi-GRU-based models for malicious traffic detection in a centralized system. The experiments are performed on a realistic cybersecurity dataset, Edge-IIoTSet.<br />   

The code will be available upon publication
