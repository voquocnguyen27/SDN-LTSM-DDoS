# SDN-LTSM-DDoS
A project using Long Term Short Memory to detect the DDoS network flows in Software Defined Networking
# Description
This project was created for my SDN course to detect network flows of DDoS attack events, including both traditional DDoS network flows and fake network flows generated by GAN networks.
# Environment
This project was implemented and completed on Kaggle.
# Dataset
In this project, I'm using the CICDDoS2019 dataset to train my model. This dataset isn't balanced, with the DDoS samples being way too large compared to the normal one. So I combined this dataset with the CICIDS2017 dataset's normal samples to balance the training data.

For the detection of fake network flows, I created a GAN model to create fake data that looked similar to the original one.

All the data can be regenerated with the code in this repository.
# Download data
You can download all data used in this project with this API command:
```bash
kaggle datasets download -d voquocnguyen/net-traffic
```
or search for "net-traffic" dataset in kaggle
