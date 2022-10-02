---
title: "Caterpillar IoT ML Analytics Challenge"
excerpt: "Submitted for HackIllinois 2020<br/><img src='/images/caterpillar.jpg'>"
collection: portfolio
---

Caterpillar has a huge array of machines that collect millions of data points from their sensors. It's almost impossible to manually check to make sure all sensor readings are accurate which is why we use anomaly detection to determine what is working and what isn't. We can then use what we learn from channel predictions to help correct problems in data collection if there is a faulty sensor.

Our model utilizes an isolation forest to locate all anomalies in our preprocessed dataset. This information is then sent to DeepAnT, a state-of-the-art deep learning approach for unsupervised anomaly detection in time series. We then use that to predict future times and we can further identify anomalies through the predictions made by DeepAnT.

See the code [here](https://github.com/nikwalia/2020_Challenge_IOT_Analytics).