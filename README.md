# Machine-Learning-approach-for-Malware-Detection
Check it out : 
<br>
 https://dipak-scanexe.herokuapp.com/
 <br>
 <br>
you can use a QR scanner app on your phone, or some camera apps :
<br>
<br>
<img src="https://github.com/DipakSalunke/malicious_exe_file_detection_using_ml/blob/master/qrcode_dipak-scanexe.herokuapp.com.png" width="150" height="150"/>

A Machine Learning approach for classifying a file as Malicious or Legitimate.

This approach tries out 6 different classification algorithms before deciding which one to use for prediction by comparing their results.
Different Machine Learning models tried are, Linear Regression, RandomForest, DecisionTree,  Adaboost, Gaussian, Gradient Boosting.

In order to test the model on an unseen file, it's required to extract the characteristics of the given file. Python's pefile.PE library is used to construct and build the feature vector and a ML model is used to predict the class for the given file based on the already trained model. 

Dependencies
============

* pandas ```pip install pandas```
* numpy ```pip install numpy```
* pickle ```pip install pickle```
* scipy ```pip install scipy```
* scikit ```pip install -U scikit-learn```
