# Supervised learning
We want to look at how January temperatures have changed over time.
#### 1. The data
     > We'll use publicly available weather data for Seattle. Let's load that and restrict it to January temperatures.
![image](https://github.com/mansi-codder/SupervisedMachineLearningModel/assets/47288219/784b6f3d-7013-4bfe-a7f3-30cf9f551ff0)

#### 2. The model
    > We'll select a simple linear-regression model. This model uses a line to make estimates
![image](https://github.com/mansi-codder/SupervisedMachineLearningModel/assets/47288219/8c6f519d-67f2-48f2-91e5-83317ca7cc23)

#### 3. The cost (objective) function
    > Our next step is to create a cost function (objective function).
    These functions in supervised learning compare the model's estimate to the correct answer. 
    In our case, our label is temperature, so our cost function compares the estimated temperature to temperatures seen in the historical records.

#### 4. Train the model
  ![image](https://github.com/mansi-codder/SupervisedMachineLearningModel/assets/47288219/9e4af852-2216-4396-8ce3-3d7484e64ded)
