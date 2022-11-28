Electromyography and Gradient Boosting 
Gradient Boosting Machines are used very often by machine learning practioners to understand how GBMs work. Understanding the mathematical machinery can be tricky and these detials are needed in order to tune the hyper-parameters. The most common form of GBM that optimizes the mean squared error (MSE) is called the L2 loss or cost. A GBM is a composite model that combines the efforts of multiple weak models to create a strong model. Each additional weak model reduces the MSE of the overall model.

![image](https://user-images.githubusercontent.com/117037344/204190930-4f6260a1-d054-44c6-9c20-e890b0ca1848.png)

![image](https://user-images.githubusercontent.com/117037344/204190880-3a6a80fc-21d2-4720-baa9-d0b5a372dce5.png)

![image](https://user-images.githubusercontent.com/117037344/204190899-529ef1ef-c782-40f9-9fc4-d330c62c869f.png)

Optimizing a model according to MSE makes it chase outliers because squaring the difference between targets and predicted values emphasizes extreme values. If an outlier cant be removed, you optimize the mean absolute erorr (MAE) which is also called the L1 loss or cost. 

![image](https://user-images.githubusercontent.com/117037344/204190986-f3436793-2fed-4799-8cdc-8f4b55b5937f.png)

![image](https://user-images.githubusercontent.com/117037344/204191036-9deeda80-71c6-44d9-99dc-76f914081ca3.png)

![image](https://user-images.githubusercontent.com/117037344/204191005-a85e1ace-c4bd-4d51-a214-aeaf0aa6fdab.png)

Gradient boosting is really doing a form of gradient descent and in fact optimizing MSE or MAE depending on the direction vectors we use to train the weak models. Involves derivative calculus

![image](https://user-images.githubusercontent.com/117037344/204191374-4e9378ba-5234-46ba-aad1-80925d5de6cd.png)

![image](https://user-images.githubusercontent.com/117037344/204191407-aa32e6c5-f2a0-4e10-8836-09bd928b9dc0.png)

![image](https://user-images.githubusercontent.com/117037344/204191419-8728114d-7e7d-4013-ad7c-740b7658b03d.png)

![image](https://user-images.githubusercontent.com/117037344/204191429-bb011c8c-15a9-4963-b231-0ee837e504c4.png)

General Algorithm with regression tree weak models

![image](https://user-images.githubusercontent.com/117037344/204191513-7e80a3ef-4830-46f2-a6c6-ceaf5ed2f395.png)

In one of the examples given, Linear Regression is referred to as a Toyota Camry, while Gradient Boosting is referred to as a UH-60 Blackhawk Helicopter.
