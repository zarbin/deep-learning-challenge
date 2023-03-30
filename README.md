# Deep Learning Challenge - Homework 21
UTA DataViz Bootcamp <br>
03/29/2023

# Summary

Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks.

I use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

Metadata:

* EIN and NAME—Identification columns
* APPLICATION_TYPE — Alphabet Soup application type
* AFFILIATION — Affiliated sector of industry
* CLASSIFICATION — Government organization classification
* USE_CASE — Use case for funding
* ORGANIZATION — Organization type
* STATUS — Active status
* INCOME_AMT — Income classification
* SPECIAL_CONSIDERATIONS — Special considerations for application
* ASK_AMT — Funding amount requested
* IS_SUCCESSFUL — Was the money used effectively


# Work and Findings

Data Preview

![image](https://user-images.githubusercontent.com/36682023/228732621-4bd6ea20-46d8-47b6-9af3-72194acd97cf.png)


## Preprocessing

![image](https://user-images.githubusercontent.com/36682023/228734144-27cc6cc7-71c5-4b90-8e4c-0d48d3e9f5e6.png)


## Compile, Train and Evaluate the Model

![image](https://user-images.githubusercontent.com/36682023/228734106-ac9a847b-3266-48bb-8211-bb5f52e74729.png)

![image](https://user-images.githubusercontent.com/36682023/228734221-7cd1387a-5340-4cb1-a9b5-9bc08c7a716d.png)

**Evaluate the model using the test data**

    268/268 - 0s - loss: 0.5616 - accuracy: 0.7299 - 211ms/epoch - 788us/step
    
    Loss:       0.5615878105163574
    Accuracy:   0.729912519454956
