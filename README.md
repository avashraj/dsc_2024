# Data Science Challenge @ Lawrence Livermore National Laboratory 2024

The data science challenge is an annual two week challenge/internship hosted at the Lawrence Livermore National Lab. This was my first experience with data science and machien learning. The challenge was split into four different tasks.

### **Task 1 & 2**
The first task was a binary classification problem comparing healthy and unhealthy hearbeats. Both tasks utilized this dataaset: [https://www.kaggle.com/datasets/shayanfazeli/heartbeat]. The second task was a multi-class classification task where there were mutliple types of abnormal heartbeats. I found xgboost classifier the most effective for both tasks with a 98% accuracy for both tasks.

### **Task 3**
The third task was more complex as we had to use synthetic 12 lead ecg data to predict heart activation times in the heart. Heart activation times refers to when electricity passes through specific points in the heart(specified by the dataset: [https://library.ucsd.edu/dc/object/bb29449106]. For this I designed and implemented a 1d convolutional neural network because 1d CNNs are useful when predicting signals. My final results from the test set was an average of 2.3 mean average error, meaning that on average the total heart activation times are only off by 2.3 milliseconds.
