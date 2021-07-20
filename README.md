
# Data and AI: Credit Default Risk Prediction

Credit Default Risk Prediction with Anaconda on IBM Z & LinuxONE

## Abstract

Financial organizations around the world face the constant challenge to accurately predict the risk of credit default. This covers all aspects of financial lending, including personal, corporate and public finance. To enhance and automate this process, great interest has been placed on the usage of data science and machine learning to predict the customers most likely to default. 

These lending processes mainly run on an institution's core business systems, with IBM Z & LinuxONE providing the industry standard platform for security, resiliency and scalability.  With Anaconda on IBM Z & LinuxONE a customer can run their machine learning model co-located to their key processes, without the need to move data off the platform, ensuring security and data currency. 

To that end, we have created an example credit default model leveraging python and conda with Linux on Z. We performed data processing and the required transformations to create a Logistic Regression model using scikit-learn. 

Model creation is inspired by source : https://github.com/ibmsoe/snap-ml/blob/master/notebooks/credit-default-prediction-example.ipynb

## Preparation

1. Ensure you follow the installation instructions [here](https://docs.anaconda.com/anaconda/) provided by Anaconda to setup your data science environment as per the architecture you are on. 

2. Create a conda environment with the following frameworks installed by running the following commands


		conda create -n credit-default --force -y scikit-learn pandas cython jpeg jupyter matplotlib
		conda activate credit-default

3. Start your Jupyter Notebook and launch via web browser using default [link](http://localhost:8888/)

		jupyter notebook

4. Import the notebook using `upload` option in the Jupyter Notebook web browser
