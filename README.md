# CRF-model-for-a-custom-NER-HealthCare-Systems
>
> This project creates a CRF model for a custom NER (Named Entity Recognition) task. The model is trained on a custom dataset of 1000 sentences. The dataset is a collection of sentences from the patient's clinical notes. The model maps diseases with their respective treatments.

## Table of Contents

## General Information

### Problem Statement

‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organize appointments, track past medical records and provide e-prescriptions.
The requirement is to build a custom NER to get the list of diseases and their treatment from the dataset.

### Dataset

The dataset consist of four files containing words in line separate format:

- train_sent
- test_sent
- train_label
- test_label

### Approach

1. Data preprocessing
2. Concept identification
3. Defining the features for CRF
4. Getting the features words and sentences
5. Defining input and target variables
6. Building the model
7. Evaluating the model
8. Identifying the diseases and predicted treatment using a custom NER

## Results

We have achieved an accuracy of 0.88 on the test set.

## Contact

Created by [@sukhijapiyush] - feel free to contact me!

## License

This project is open source and available under the [Apache License].
