# Naïve Bayes Spam Detection
The enron1 and enron6 data sets include thousands of emails. Some of them are spam and some of them are ham (non-spam).

In the python notebook “Naive_Bayes_Spam_Detection”, I implement the Naïve Bayes learning algorithm from scratch; that is, I do not use any built-in Naïve Bayes function or package. I try to predict whether an email is spam.

The code in the python notebook file randomly splits the enron1 and enron6 datasets into two as “Train” (70%) and “Test” (30%). Then, different models; first trained from “enron1_Train”, and second from “enron6_Train” were created. Both of the models were used to make prediction on “enron1_Test” and “enron6_Test” datasets. So, there are 4 different cases in total. The prediction accuracy and confusion matrices for each of these 4 cases were calculated.<br><br><br>


# Prediction Accuracies and onfusion Matrices
As the two prediction models were generated based on randomly split datasets; the whole python notebook was run 5 times and the average prediction accuracies and confusion matrices for each run are reported:
<img width="497" alt="Final Table" src="https://user-images.githubusercontent.com/75792293/102027036-a7958880-3db2-11eb-85f5-135355e49ecb.png">
