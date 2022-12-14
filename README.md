# Speech Emotion Recognition (SER)
<p align="justify"> Speech emotion recognition (SER) is the ability to identify the type of emotion from human speech, intending to create a natural interaction between humans and computers or commonly known as human-computer interaction (HCI). To increase human satisfaction while using digital devices such as computers and smartphones, the development of HCI is very much needed. Therefore, in this project, I will design a Speech Emotion Recognition (SER) system using Linear Predictive Coding (LPC) with K-Nearest Neighbor (KNN) classification. </p>

<h2> Prepare Dataset </h2>
<p align="justify"> The dataset used in this project is a primary (self-collected) dataset. The collection process was carried out in one of the Telkom University laboratories. The dataset was collected with the help of 20 actors (10 men and 10 women). Of all the datasets collected, the data that has the best quality will be taken and selected.
<br/>The procedure for collecting datasets:<br/>
1. Dataset collection was carried out in the Telkom University laboratory room.<br/>
2. Determine the sentence that will be used in the dataset retrieval process. In this case the sentence used is "Dia pacar saya".<br/>
3. Each actor will say the sentence in 4 types of emotions (angry, happy, sad, disappointed), where each emotion will be repeated 10 times.<br/>
4. Each sentence spoken by the actor will be recorded and saved in .wav format. </p>

<h2> Data Augmentation </h2>
<p align="justify"> Augmented data has a significant role in improving the performance of the DNN model and reducing overfitting. Data augmentation is a way to increase the amount of data and is very useful for processing small data. In augmentation of speech recognition data on DNN can be used to improve accuracy.</p>

<h2> Linear Predictive Coding (LPC) </h2>
<p align="justify"> Linear predictive coding is one method that is often used for feature extraction in speech recognition. The most crucial aspect of LPC is the linear predictive filter which allows the value of the following sample to be determined by a linear combination of the previous models. The linear predictive method reduces the mean square error between the input signal and the signal to be estimated to obtain a filter coefficient equivalent to that of the vocal channel.</p>

<h2> K-Nearest Neighbor (KNN)</h2>
<p align="justify"> The KNN classification belongs to the machine learning supervised learning group. The intuition underlying the KNN classification algorithm is straightforward, namely by classifying based on the class of its nearest neighbor (nearest neighbor). The basic principle of the nearest neighbor method is to measure the distance between the unknown signal pattern and the reference signal pattern in the database. The Euclidean distance equation is used to calculate the distance, which is one of the implementations in the nearest neighbor algorithm.</p>
