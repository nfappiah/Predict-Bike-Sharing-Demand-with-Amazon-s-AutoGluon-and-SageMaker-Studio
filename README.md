# Predict Bike Sharing Demand with Amazon's AutoGluon and SageMaker Studio

In this project, I predict bike rental demand using Amazon's AutoGluon. AutoGluon is an open-soure ML Library whose major advantage is the automatic training of several machine learning models simultaneously, enabling you to choose the model that gives the best results. This project is a Kaggle competition and details can be found at: [https://www.kaggle.com/competitions/bike-sharing-demand/overview](https://www.kaggle.com/competitions/bike-sharing-demand/overview)

## Dataset

The dataset can be found at: 
[https://www.kaggle.com/competitions/bike-sharing-demand/data](https://www.kaggle.com/competitions/bike-sharing-demand/data)

## Materials and Packages

* Amazon SageMaker Studio
* Jupyter Lab
* Jupyter Notebook
* Python 3.7
* MXNet 1.8
* Pandas >= 1.2.4
* AutoGluon 0.2.0 

## Instructions 

* To run the jupyter notebook, users must download the Kaggle API key/token (a kaggle.json file) and place it in the working directory (same directory as the jupyter notebook). Alternatively, one can directly download the dataset on the Kaggle website and upload it in the working directory.
* If using Amazon Sagemaker Studio, the Notebook should be using a ml.t3.meduim instance (2 vCPU + 4 GiB) and kernel: Python 3 (MXNet 1.8 Python 3.7 CPU Optimized)
* For local development, you will need to setup a jupyter lab instance. Follow the [jupyter install](https://jupyter.org/install.html) link for best practices to install and start a jupyter lab instance. If you have a python virtual environment already installed you can just pip install it (pip install jupyterlab)
* The entire notebook can be run at once by pressing Ctrl + F9. However, it is recommended to run the notebook one cell at a time to observe the output. A code cell can be run by selecting it and pressing Ctrl+Shift+Enter or Shift+Enter
* To submit your score to the Kaggle compettion, if you wish, you must create a Kaggle account and accept the terms and conditions of the competition. Visit the [Kaggle Bike Sharing Demand Competition](https://www.kaggle.com/c/bike-sharing-demand) page for more information. There you will see the overall details about the competition including overview, data, code, discussion, leaderboard, and rules. You will primarily be focused on the data and ranking sections.

## Acknowledgements

I am grateful to AWS for awarding me the AWS AI & Machine Learning Scholarhip to pursue the nanodegree in "Machine Learning Fundamentals" through Udacity. This Jupyter notebook represents the first out of four projects I undertook as part of the requirements to complete the nanodegree.