# Project: Lung X-ray
This is the final project for my machine learning course. It is a multi-label classification problem to detect 4 types of Lung X-ray images.

## Problem Setup
With the fast spread of COVID-19, researchers in the statistical learning community have started to explore methods to faster detect the affected patients. One of these methods is an automated system which can help the physicians classify the type of lung problem from the patient’s xray image. This is specifically useful because the test kits are not available to all countries of the world, whereas basic imaging systems like xray are the standard medical technologies within the majority of countries.

In this project, we are planning to come up with a prototype system to perform this task. Due to the limited computational resources, we would only explore three types of lung problems. All three problems can pose serious threats to the respiratory system. For technical reasons, the scientific names of the deceases are not disclosed and we only refer to them as types A, B, C and normal. Please note that COVID-19 is among these three problematic cases.

In the project folder, you have access to four folders. Each folder contains couple of hundred xray images of the patients having the same problem.

* The folder **Type A** contains 643 cases of the xray of patients affected by the type A decease.
* The folder **Type B** contains 253 cases of the xray of patients affected by the type B decease.
* The folder **Type C** contains 285 cases of the xray of patients affected by the type C decease.
* The folder **Normal** contains 1212 cases of the xray of patients who were identified as normal, with none of the aforementioned issues.

All the images for the training and test are of size 1024×1024 (please down-scale or up-scale to this size in case you observe a sample with a different size than this). I under- stand that 1024×1024 is a large dimensionality for the feature space, and you may explore dimensionality reduction techniques, or down-sampling methods to reduce the size of the images for your machine learning purposes. Note that if you just simply pass the raw data to a training module, it may take a long time to train the model, and might also limit the CPU/GPU access of the other classmates using the cluster. Please explore ideas which allow working with smaller feature sets.

## Model Evaluation
* Training Accuracy: 96.5%
* Training Loss: 0.115
* Predictions were made on the testing files, which acchieved an accuracy of 87.97%.

