# Fraud Detection
Dataset: https://www.kaggle.com/competitions/ieee-fraud-detection/data <br>
The purpose of this code is to use a combination of an Autoencoder and a Classifier on the data we have of each individual to detect fraudulent transactions. To do so, I have trained my model once, using both transaction and identity data and once using transaction data. The general approach is semi-supervised learning. <br>
Below, you can see the structure of the Autoencoder and Clasiffier Models designed by using both identity and transaction data.<br>
Autoencoder:
<div align=center>
  <img src="./assets/identity and transaction.PNG" width="400"/>
</div>

<br>
Classifier:
<div align=center>
  <img src="./assets/classifier identity transaction.PNG" width="400"/>
</div>

<br>
Using these two models, I reached an accuracy of %97 through 100 epochs.<br>
Keras, Sklearn, and Matplotlib are libraries that I have used in this code.
