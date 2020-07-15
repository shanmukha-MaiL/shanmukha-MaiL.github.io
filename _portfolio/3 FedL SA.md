---
title: "Federated Learning for Sentiment Analysis using Neural Networks"
excerpt: "A combination of Federated Learning and Sentiment Analysis<br/><img width='500' height='400' src='/images/FedL webUI.png'>"
collection: portfolio
---

As a part of Minor Project we tried to integrate two different research fields namely Federated Learning and Sentiment Analysis. We experimented with a newly open sourced (at the time of our project) tensorflow-federated library to see the impact of federated training setup on sentiment analysis task. Special thanks to my teammates [Vinay](https://www.linkedin.com/in/vinay-kornapalli-96b176127/), [Karthik](https://www.linkedin.com/in/karthik-reddy-889257130/) and mentor [Dr. Manu Vardhan](http://www.nitrr.ac.in/viewdetails.php?q=cs.mvardhan) for their support.<br>
**Data:** We extracted the data from [sentiment140](https://www.kaggle.com/kazanova/sentiment140) and modified it according to the federated data format.<br>
**Algorithm:** BiLSTM, ELMO, Federated averaging<br>
**Major tool(s):** *Tensorflow, Keras, Tensorflow-federated, NLTK, Numpy, Pandas*<br>

**An image of the web UI of the project:**<br><br>
<img width="100%" height="500" src='/images/FedL webUI.png'>

**Loss VS Rounds (Different than epochs):**<br><br>
<img width="100%" height="500" src='/images/FedL graph.png'>
