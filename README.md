# Project Title: Operationalizing Machine Learning


## Project Summary

The dataset (https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/bankmarketing_train.csv) used in this project contains data about marketing campaign of a Portuguese banking institution and we seek to predict if the client will subscribe to a term deposit (variable y in the dataset).

![Work-flow](https://user-images.githubusercontent.com/65784601/105206319-86108500-5b46-11eb-948e-5d21e3086e94.png)

# Description of stages that make up the overall flow
#### 1. Authentication
Authentication is crucial for the continuous flow of operations. Continuous Integration and Delivery system (CI/CD) rely on uninterrupted flows. When authentication is not set properly, it requires human interaction and thus, the flow is interrupted. An ideal scenario is that the system doesn't stop waiting for a user to input a password. So whenever possible, it's good to use authentication with automation.
##### Authentication types
###### Key-based
###### Token based
In this project I used Azure Container Instances service which is a Key-based authentication.

### Registering Dataset

![ds import](https://user-images.githubusercontent.com/65784601/105210144-f4574680-5b4a-11eb-94d1-4474c3655480.png)




### Used STANDARD_DS12_V2 Machine size

![running compute](https://user-images.githubusercontent.com/65784601/105210172-ff11db80-5b4a-11eb-896a-a1f038182094.png)



### Best model after completion is VotingEnsemble

![completed exp](https://user-images.githubusercontent.com/65784601/105210389-3ed8c300-5b4b-11eb-81ed-ffb15099c5f4.png)



## Deploy Best Model

### Used Azure container Instance and enabld authentication

![model setup](https://user-images.githubusercontent.com/65784601/105210425-4ef0a280-5b4b-11eb-9cf4-716b8856ba7c.png)



### Model Deployed

![model-deploy](https://user-images.githubusercontent.com/65784601/105210435-531cc000-5b4b-11eb-93db-0196a7877740.png)

### Updating and running logs.py
![log](https://user-images.githubusercontent.com/65784601/105213453-0509bb80-5b4f-11eb-83aa-8cc1ba0a3fda.png)

### Application insights enabled and accessed from the endpoints
![app-insight](https://user-images.githubusercontent.com/65784601/105213472-0935d900-5b4f-11eb-8ef3-c759e47df89f.png)

#### 2. Automated ML Experiment
#### 3. Deploy the best model
#### 4. Enable logging
#### 5. Swagger Documentation
#### 6. Consume model endpoints
#### 7. Create and publish a pipeline
#### 8. Documentation

