# Problem Context
With the enormous growth of computer networks usage and the huge increase in the number of
applications running on top of it, network security is becoming increasingly more important. All
the computer systems suffer from security vulnerabilities which are both technically difficult and
economically costly to be solved by the manufacturers. Therefore, the role of Intrusion Detection
Systems (IDSs), as special-purpose devices to detect anomalies and attacks in the network, is
becoming more important.<br><br>
The research in the intrusion detection field has been mostly focused on anomaly-based and
misusebased detection techniques for a long time. While misuse-based detection is generally
favored in commercial products due to its predictability and high accuracy, in academic research
anomaly detection is typically conceived as a more powerful method due to its theoretical
potential for addressing novel attacks.<br><br>
Conducting a thorough analysis of the recent research trend in anomaly detection, one will
encounter several machine learning methods reported to have a very high detection rate of 98%
while keeping the false alarm rate at 1%. However, when we look at the state of the art IDS
solutions and commercial tools, there is no evidence of using anomaly detection approaches, and
practitioners still think that it is an immature technology. To find the reason of this contrast, lots
of research was done done in anomaly detection and considered various aspects such as learning
and detection approaches, training data sets, testing data sets, and evaluation methods.<br><br>

# Problem Statement
Our task is to build network intrusion detection system to detect anamolies and attacks in the
network. There are two problems.<br>
1. **Binomial Classification**: Activity is normal or attack
2. **Multinomial classification**: Activity is normal or what kind of attack is it (DOS or PROBE or R2L or U2R)

## Approach
For *Binomial Classification*, **Logistic Regression** is used.<br><br>

For  *Multinomial Regression*, following methods were tried: <br>
- GridSearchCV was used to identify best parameters for the model algos utilized for prediction
- KNN Classifier : did not provide enough accuracy
- **SVM for Multiclass Classification**, with *rbf* kernel. Feature engineering was done based on
  - RandomForest Classifier
  - Select K-Best Variables
