# MNIST-Image-Recognition-Based-on-Xgboost-algorithm-and-Features-extraction
#### Introduction
- Different from the common practice of MNIST image recognition using CNN algorithm, I apply NumPy and OpenCV to extract relevant features from each MNIST figure, and then trains Xgboost recognition model. After gradually adjusting parameters, the accuracy of the optimal model on the test set can reach 88%.
- Because I've made extensive use of the broadcasting mechanism of NumPy instead of loops when coding, the code can run at an excellent speed.
#### File loaded
- Train set: train-labels.gz (label) + train-images-idx3-ubyte.gz (featrues)
- Test set: test-labels.gz (label) + t10k-images-idx3-ubyte.gz (featrues)
#### Notice
- It's necessary to unzip files suffixed with '.gz' before running the code.
#### Copyright notice
- AUTHOR: Yingxin LIN
- Company: School of Finance, Central University of Finance and Economics (CUFE)
- Contact: lyxurthebest@163.com or lyxurthebest@outlook.com
- The copyright belongs to Yingxin LIN, 2021/08/11.
#### Enjoy（。＾▽＾) 😊! (...and extend/modify)
