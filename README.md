Electromyography and Gradient Boosting 
Gradient Boosting Machines are used very often by machine learning practioners to understand how GBMs work. Understanding the mathematical machinery can be tricky and these detials are needed in order to tune the hyper-parameters. The most common form of GBM that optimizes the mean squared error (MSE) is called the L2 loss or cost. A GBM is a composite model that combines the efforts of multiple weak models to create a strong model. Each additional weak model reduces the MSE of the overall model.

![image](https://user-images.githubusercontent.com/117037344/204190930-4f6260a1-d054-44c6-9c20-e890b0ca1848.png)

![image](https://user-images.githubusercontent.com/117037344/204190880-3a6a80fc-21d2-4720-baa9-d0b5a372dce5.png)

![image](https://user-images.githubusercontent.com/117037344/204190899-529ef1ef-c782-40f9-9fc4-d330c62c869f.png)

Optimizing a model according to MSE makes it chase outliers because squaring the difference between targets and predicted values emphasizes extreme values. If an outlier cant be removed, you optimize the mean absolute erorr (MAE) which is also called the L1 loss or cost. 

![image](https://user-images.githubusercontent.com/117037344/204190986-f3436793-2fed-4799-8cdc-8f4b55b5937f.png)

![image](https://user-images.githubusercontent.com/117037344/204191036-9deeda80-71c6-44d9-99dc-76f914081ca3.png)

![image](https://user-images.githubusercontent.com/117037344/204191005-a85e1ace-c4bd-4d51-a214-aeaf0aa6fdab.png)

